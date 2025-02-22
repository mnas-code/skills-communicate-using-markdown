# This is my first Markdown Header.
###### I feel like this will mark a new beginning in my SWE journey.

First of all, a simple introduction to my languages:

| Rank | Language   |
|-----:|------------|
|     1| Swift      |
|     2| Python     |
|     3| Javascript |

Although I am still learning a lot.
<!-- I should probably include more about what steps I am taking in my learning journey -->

## Below is an example of a responsive Markdown image.

<details>
<summary>Here's the picture</summary>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
</details>

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

### Below is a tasks list.

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
