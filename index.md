# Immersive Web Early Adopters Guide

This material is draft documentation intended for use by those experimenting with the WebXR Device API and related specs. It is modeled after the API documentation in MDN web docs. Because the spec it applies to is still under development, it does NOT go as deep as its MDN cousin. The work here is mostly confined to interface descriptions. The only exceptions are where more depth is deemed necessary than is provided by the interface page.

This material is intended to be temporary. As soon as WebXR lands in a stable version of a browser, the material here will be copied to MDN and this repository will be deprecated.

Feedback and pull requests are welcome.

## APIs

* [WebXR Device API](webxr-device-api/index.md)

## Spec Notes

The web and web specs are always evolving. New specs like the Immersive web
can undergo changes that would never be made to a mature production-ready spec.

The following table shows changes that may require corrections to your code.

| Change | Browser/date | Description |
| ------ | ------------ | ----------- |
| `XRPresentationFrame` became `XRFrame` | Chrome 69/June 2019 | [More information](https://github.com/immersive-web/webxr/issues/364). |
| Frame of reference names changed. | Chrome 69/June 2018 | The values that may be passed to `[requestFrameOfReference()](webxr-device-api)` changed from `"headModel"` and `"eyeLevel"` to `"head-model"` and `"eye-level"`. `"stage"` remained unchanged. [More information](https://github.com/immersive-web/webxr/issues/364). |

## Browser Compatibility

| -- | -- | -- |
| AR hit test support | Chrome Canary for the foreseeable future. | Enable the #webxr and #webxr-hit-test flags under chrome://flags. Requires Android O or later. |
| VR use cases | Chrome 66 and later | Enable the chrome://flags/#webxr flag. (The URL must be entered manually.) |
| VR use cases | Chrome 67 origin trial | Enable the chrome://flags/#webxr flag *and* sign up for the origin trial ([explainer](https://github.com/GoogleChrome/OriginTrials/blob/gh-pages/developer-guide.md), [sign-up form](http://bit.ly/OriginTrialSignup)). |
