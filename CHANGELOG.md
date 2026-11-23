# Changelog

## 1.1.0

- Security: reject unsafe file names from the checkout page when sharing, and disable file and content access in the checkout WebView.
- Remove the transitive `com.klarna.mobile:sdk` dependency. If your app imports `com.klarna.*` classes without declaring that dependency itself, add it explicitly.
- Send the app's Kotlin version and `minSdk` in the checkout handshake.

## 1.0.3

- Fix R8 stripping strong references with AGP 9.

## 1.0.2

- Fix checkout view getting stuck after payment.

## 1.0.1

- Remove runtime config.

## 1.0.0

- Initial release.
