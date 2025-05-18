# Vecto Icons


[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**Vecto Icons** is a powerful and lightweight Android icon library built specifically for **Jetpack Compose**. With over **5880+ Material Design icons**, it eliminates the need to manually search and import vector assets. Vecto follows Google's icon design system and provides both **Filled** and **Outlined** variants, making it incredibly easy to design clean and scalable UIs.

---

## ✨ Why Vecto?

- 🔥 **5880+ Icons** — Huge collection of Material icons.
- 🎨 **Two Variants** — Filled and Outlined, auto-generated and consistent.
- ⚡ **Lightweight** — Optimized for Jetpack Compose, with minimal overhead.
- 🛠️ **Easy to Use** — No more searching SVGs or XMLs. Just type and go!
- 📁 **Organized** — Icons grouped and named semantically.
- ⏱️ **Time-Saving** — Speeds up your UI development workflow.
- 💎 **Pixel-Perfect** — Crafted to match Google’s Material Design standards.

---



## 📦 Installation


### Step 1: Add the JitPack repository

In your **`settings.gradle.kts`** or **`settings.gradle`**:


```kotlin
dependencyResolutionManagement {
    repositories {
        maven("https://jitpack.io")
        google()
        mavenCentral()
    }
}


```

### Step 2: Add the Vecto Icons dependency
```kotlin
 implementation("com.github.0xJihan:Vecto-Icons-Library:2.0.0")
```


## 📖 Usage
```Kotlin

Icon(
imageVector = Vecto.Filled.Home,
contentDescription = null
)

```

---

## 📲 Try Out Demo APK

Want to see Vecto Icons in action? Download and try the demo app!

[![Download Demo](https://img.shields.io/badge/Download-Demo%20APK-blue?logo=android)](https://raw.githubusercontent.com/0xJihan/Vecto-Icons/main/app/release/app-release.apk)

> 🔐 Note: You may need to allow installation from unknown sources on your Android device.

---



## 📄 License

Computils is licensed under the [MIT License](https://opensource.org/licenses/MIT).


