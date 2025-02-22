# This is my first Markdown Header.
###### I feel like this will mark a new beginning in my SWE journey.

## Below is an example of a Markdown image.

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

## Below is a code snippet.

```swift
func signInWithApple() {
      logDebug("Initiating Apple Sign In process", category: "AppleSignInViewModel")
      let request = ASAuthorizationAppleIDProvider().createRequest()
      request.requestedScopes = [.fullName, .email]
      let controller = ASAuthorizationController(authorizationRequests: [request])
      controller.delegate = self
      controller.performRequests()
  }
```
