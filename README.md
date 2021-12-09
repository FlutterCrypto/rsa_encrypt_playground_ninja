# rsa_encrypt_playground_ninja

RSA encryption

For more information see here: http://fluttercrypto.bplaced.net/rsa-encrypt-playground-ninja/

```plaintext
https://pub.dev/packages/ninja
https://github.com/ninja-dart/ninja
ninja: ^3.0.7

https://pub.dev/packages/url_launcher
url_launcher: ^6.0.12

https://pub.dev/packages/path_provider
path_provider: ^2.0.5

in AndroidManifest.xml ergänzen:

    <queries>
        <!-- If your app opens https URLs -->
        <intent>
            <action android:name="android.intent.action.VIEW" />
            <data android:scheme="https" />
        </intent>
    </queries>
```    

```plaintext
-----BEGIN PRIVATE KEY-----
MIIEvAIBADANBgkqhkiG9w0BAQEFAASCBKYwggSiAgEAAoIBAQCPBHOdOM+ZsXFe
Fo1FX6KinBVXdX0GjOth0jTvaQveKjt3rELYUAMEAGsCwmy7igeFOF02gqKDJao5
oyX6KHzHpDpLSqrmo+k7liPb4MGTtZZ6UNnyrDEIDVfveqBvhqjj8l5T5tooLmJ4
QrjVtIHwD+IaxRDuPaDULseirpBZ9vVfblhkhKoJ2Tl9LXmzx/rV6+cz3nmf+5nZ
nmLdqY7eb2z6UmRS5slUWpW/NsnRyPrFdPL6Hy0TodhUfrFmBhDVfejQlCZHfHKB
6NJYPz3aombQ7KL/KGL6MuhYyzL5FKlPiyc/QBxqVC4/dlZJIpMK42FI8CjDNf5v
Hz3+N81RAgIQAQKCAQBJsMBJ0tpQoNlP2MHi0sy04wMPkiP9UGuJAbYMwmdnWW5v
FmZM9u0fDgZGV65vAIM4BTw2hItYwa1QP4FqhpVlzdbtvu+FRcWnyzRn26gJj81A
1f3zomRe0HN6xJbGDhXJnh+bZBPN2IpXNW/Lpv1H1LJMhyf3SW58cxTSGrXZ/1GN
fNf4eutp+FoI/vdR1d5l2Qw3p1kMmJ4TdLJiV+hYoyDZJsuGYEWcRBUNhf7Mko2v
VAV8CZ/s/a8Ct1f04NH5oi1o2WNMwAe+Pf5/YLAlQBpT4RVX4kwr00/iZKdKp8cr
FwXZpuLb0yOOPj5L+AEMOtAOjPk/L4WZLNjdsXhNAoGBAMsCVtsL3zM519fD0pWJ
M9vbaePcA1SG8CBo5pfbQJPY8yGU3mGUWv+y+O5D9fm7iV5mll8TxvPgaZ2HzjeH
LC1p91uC2yaT5FfHPnCwEduLNPcTqrEyuzJVjslBl+5KdyJ9dBERgZ1N2dUcU+Am
ndJDhwKza2xRyIjJuWuhoTRrAoGBALRZSg+NUcPAu7NZUCohCUyrM7hVtl+nliYl
+JlO0xuWs2NxqxUnYOQvCmQQe/Ag7NpmCDaMt0t1dZnFej4glAlyi7WZCA9SqcgI
chgsS6eNns5Jo8h/PXPxeulu+mlESfWamKsknWkV7Dbvin6A5BEWVz9zlD41+qxy
x5kJhhQzAoGAWLIak1CbINDaJchXIac7FgMitEiBbHmwlSCFvUEcxtACQCjsICKz
GUzBvQQi3FUPVyuiPKj6AjOO7sjMsbkW3OrgSxkd85ynn2I8RbqWJG8u0oyPbzkX
/R9R0RZ43bTvgTp/cP52nTSSSN0zVF+aPp9YqsN8WjCaeR+V7opZrS0CgYAhf77W
lkgcbLgUAQfkVX3yb2fVchWQzIYNFZymMVIDr/S03oBxFw9/bQaNznMfmyRPDqP8
Yr6iCuH7QgxlZJc3jd82+c7yaaUQ6QMia5QVD+7SRmoXTq7v646tE90oXDo6Dege
yhDdyEYukfgLoBhd5tgoN2XEcqA4pojM0gfYowKBgQCZnNsd/kaevBa5wvgzeAyI
NgiQTqy4TU8ydtvX00bU8oCAsdSD4IshqmvgiE/NHF12C4FbZ6VO4GSUpuu+bkZH
T27JSEghEsyjCxF6jLn8LlEVqywqbTaDR6bNX1EdUyE1VrjVmcgw6+AvF63xCYss
jfeDVW2Op3m8jmM6mRdfag==
-----END PRIVATE KEY-----
```


```plaintext
-----BEGIN PUBLIC KEY-----
MIIBITANBgkqhkiG9w0BAQEFAAOCAQ4AMIIBCQKCAQEAjwRznTjPmbFxXhaNRV+i
opwVV3V9BozrYdI072kL3io7d6xC2FADBABrAsJsu4oHhThdNoKigyWqOaMl+ih8
x6Q6S0qq5qPpO5Yj2+DBk7WWelDZ8qwxCA1X73qgb4ao4/JeU+baKC5ieEK41bSB
8A/iGsUQ7j2g1C7Hoq6QWfb1X25YZISqCdk5fS15s8f61evnM955n/uZ2Z5i3amO
3m9s+lJkUubJVFqVvzbJ0cj6xXTy+h8tE6HYVH6xZgYQ1X3o0JQmR3xygejSWD89
2qJm0Oyi/yhi+jLoWMsy+RSpT4snP0AcalQuP3ZWSSKTCuNhSPAowzX+bx89/jfN
UQICEAE=
-----END PUBLIC KEY-----
```

Klartext:
```plaintext
The quick brown fox jumps over the lazy dog
```

```plaintext

```

Sample OAEP encryption
```plaintext
{
"algorithm": "RSA-2048 OAEP SHA-1",
"ciphertext": "YLPN0DJv0aVhd2o0tjWLYMeJgEG5l+n3z9+1lfsQftXuTpXPP9I9fzy6UH2h4mIMPNVh++7yV5S0UanSJ7kGrZI9blUeHq9jaI+MG+CWr0u8C40sIBVqL+ElL/ISmR9DfYgYgFljT4UIB9Kldnrrep4aegWObR+WAtWzd1VyJjRtJ4SGu0mMr3LE1NcBTpsdq8Hku912iOkjp2EYXIPwzjcKtAWtTJAq+BlB+Os8Oi6vqjMPCFi97GUNEvLZ25VWYw9D41j3zGNTC7effncQ0AMxSPEMMKvXnLBoRfVY4BK+jUe1T8vsQ+2X9BCX851mbaTEPJEzCh78yDqLouvdqQ=="
}
```

Sample PKCS 1.5 encryption
```plaintext
{
"algorithm": "RSA-2048 PKCS 1.5",
"ciphertext": "e0LKyNAdWEg9Xntj7XV+YYfG/0/ncQ1w52eg9Oh2P6YCsoJM6Mn6yVTUjMjgi9Z4IVEz+jqghnNkDXPHuWRLYClIYsN+UPQAkgBEzVQQYnfWFOOLxZQlIv1q66PHbP3efSutBvF9l/MwdzPZqRFvaVZxmy2hL9rH4WBep3bvA9fKGUkrlzLJGvl9KeM9JhEaoFZAeqBcoKuXyh3C+BmtSSt6Za3aL2LLcknufxAMqNlpUnfiAkcCGtQsPLgtlb2927NV7qSTHyE1QB+yvWYRa/YwuEdWN6UDAflAysXL0EtlOMnUiQX9EcwbLIgn1z9nwQdMUiUURdcANhgNIeNAzQ=="
}
```

development environment:
```plaintext
Android Studio Arctic Fox Version 2020.3.1 Patch 3
Build #AI-203.7717.56.2031.7784292
Runtime version: 11.0.10+0-b96-7249189 aarch64
VM: OpenJDK 64-Bit Server VM
Flutter 2.5.3 channel stable Framework Revision 18116933e7
Dart 2.14.4
```

tested on:
```plaintext
Android Simulator: 
  Android 11 (SDK 30) Emulator,
  Android 12 SV2 (SDK 31) Emulator, 
  Android 6 (SDK 23) Emulator,
  Android 5 (SDK 21) Emulator.
iOS Simulator:  
  iOS 15 Emulator
  iOS 11.4 Emulator 
```


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
