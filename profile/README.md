# 👋 Welcome to Approov

Since 2001, Approov has been providing mobile app protection and mobile API security for apps on Android, iOS, and HarmonyOS. 

Here, you'll find open source quickstarts, SDK examples, service layers, and more to help you learn how to integrate Approov into your mobile apps.

Approov helps teams protect APIs from:
- fake or repackaged mobile apps
- bots and scripted API abuse, such as app scraping
- stolen API keys and embedded secrets
- man-in-the-middle attacks
- unauthorized clients calling mobile APIs directly
- compromised or risky runtime environments

## ❓ What Approov does

Approov verifies that API requests come from genuine, untampered mobile apps running in trusted environments. Verified apps receive short-lived Approov tokens or runtime secrets that backend services can validate before allowing API access.

How we do it:

- Mobile app attestation
- Runtime Application Self Protection, or RASP
- Mobile API protection
- Runtime secrets protection
- Dynamic certificate pinning
- Token binding and JWT validation
- Real-time mobile threat intelligence

## 🎯 Start here 

### Popular repositories

- [shipfast-api-protection](https://github.com/approov/shipfast-api-protection) — practical mobile API security walkthrough
- [react-native-cert-pinner](https://github.com/approov/react-native-cert-pinner) — certificate pinning for React Native
- [quickstart-react-native](https://github.com/approov/quickstart-react-native) — Approov integration for React Native apps
- [quickstart-flutter-httpclient](https://github.com/approov/quickstart-flutter-httpclient) — Approov integration for Flutter mobile apps
- [approov-service-okhttp](https://github.com/approov/approov-service-okhttp) — Android service layer for OkHttp
- [approov-service-urlsession](https://github.com/approov/approov-service-urlsession) — iOS service layer for URLSession

### Mobile app quickstarts 

| Platform or framework | Example repositories |
|---|---|
| Android | [Android Java HttpsUrlConnection](https://github.com/approov/quickstart-android-java-httpsurlconn), [Kotlin OkHttp](https://github.com/approov/quickstart-android-kotlin-okhttp), [Kotlin Retrofit](https://github.com/approov/quickstart-android-kotlin-retrofit), [Java Volley](https://github.com/approov/quickstart-android-java-volley)|
| iOS | [Objective-C](https://github.com/approov/quickstart-ios-objectivec-nsurlsession), [Swift URLSession](https://github.com/approov/quickstart-ios-swift-urlsession), [Swift Alamofire](https://github.com/approov/quickstart-ios-swift-alamofire), [WebView](https://github.com/approov/approov-service-ios-webview)|
| Cross-platform | [React Native](https://github.com/approov/quickstart-react-native), [Flutter Httpclient](https://github.com/approov/quickstart-flutter-httpclient), [Cordova](https://github.com/approov/quickstart-cordova-advancedhttp), [Unity](https://github.com/approov/quickstart-unity-web-request) |

### Service layers
Approov service layers are wrappers for the [Approov SDK](https://github.com/approov/approov-ios-sdk) to enable easy integration with your build. 

Some popular examples include: [React Native](https://github.com/approov/approov-service-react-native), [URL Session](https://github.com/approov/approov-service-nsurlsession), [OK Http](https://github.com/approov/approov-service-okhttp), [Volley](https://github.com/approov/approov-service-volley), [Retrofit](https://github.com/approov/approov-service-retrofit), [Android WebView](https://github.com/approov/approov-service-android-webview), [Https Url Connection](https://github.com/approov/approov-service-httpsurlconn), [Moya](https://github.com/approov/approov-service-moya), [Alamofire](https://github.com/approov/approov-service-alamofire), and many more! 

Our service layers are all open source. If you're looking for one in particular, you'll find them all when searching our organization on GitHub.


### Backend and API verification 

Use these examples to validate Approov tokens before allowing traffic to reach protected APIs.

| Backend or gateway | Example repositories |
|---|---|
| Node.js | [Express](https://github.com/approov/quickstart-nodejs-express-token-check) and [General](https://github.com/approov/quickstart-nodejs-token-check) token checks |
| Python | [Flask](https://github.com/approov/quickstart-python-flask-token-check) and [FastAPI](https://github.com/approov/quickstart-python-fastapi-token-check) token check examples |
| PHP | [Laravel and generic PHP token checks](https://github.com/approov/quickstart-php-laravel-token-check) |
| Azure | [Azure Functions and API Management](https://github.com/approov/approov-token-verifier-azure-functions) |

## 📚 Documentation and resources 

- Developer docs: https://approov.io/docs/
- Quickstarts: https://approov.io/resource/quickstarts/
- Changelog: https://approov.io/changelog
- Blog: https://blog.approov.io/
- Free trial: https://approov.io/signup/

### Learn mobile API security concepts 

| Repository | Use case |
|---|---|
| [shipfast-api-protection](https://github.com/approov/shipfast-api-protection) | Walkthrough of API keys, static HMAC, dynamic HMAC, dynamic certificate pinning, and mobile app attestation |
| [hands-on-api-proxy](https://github.com/approov/hands-on-api-proxy) | Learn how to remove API keys and secrets from mobile apps using an API proxy |

