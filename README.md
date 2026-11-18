<img width="1220" height="2712" alt="Screenshot_2026-11-18-17-38-06-187_com cynide indcoolremote jpg" src="https://github.com/user-attachments/assets/2697a609-227a-45b3-9436-4aeb319d4fc1" />
<img width="1220" height="2712" alt="Screenshot_2026-11-18-17-37-55-281_com cynide indcoolremote jpg" src="https://github.com/user-attachments/assets/2dc82518-03f7-47c0-bfd6-60f4f9c99f0d" />
<img width="1220" height="2712" alt="Screenshot_2026-11-18-17-33-59-265_com android vending jpg" src="https://github.com/user-attachments/assets/42fb3ba8-15bc-47c3-9dfd-87d4c2bbe48a" />
<img width="1220" height="2712" alt="Screenshot_2026-11-18-17-33-36-201_com android vending jpg" src="https://github.com/user-attachments/assets/dd0a1e2b-99f7-41b1-ba2a-3a813bf82553" />
# ❄️ INDcool AC Remote

A modern, lightweight, standalone Android Infrared (IR) remote control application built specifically for **INDcool Split Inverter Air Conditioners**. Engineered in native Kotlin with zero ads, zero internet permissions, and instant offline IR transmission.

**Made with ♥️ by CYNIDE**

---

## ✨ Key Features

- **Digital LCD / OLED Live Status Display:**
  - Real-time temperature readout (**16°C – 30°C**) and clean **OFF** standby display.
  - Live status pills for **Active Mode**, **Fan Speed**, **Timer**, and **Airflow Direction**.
- **Pitch-Black AMOLED Night Mode & Clean Day Mode:**
  - Single-tap circular **Sun / Moon** theme toggle in the top header with persistent preference saving.
- **Complete AC Controls:**
  - **Controls:** Power, Swing, Direction (5-step louver positioning), and Sleep Mode.
  - **Temperature:** Tactile `TEMP -` and `TEMP +` controls (`16°C` to `30°C`).
  - **Modes:** Cool, Dry, Fan, Auto, and Heat.
  - **Fan Speed:** Auto, Low, Medium, and High.
  - **Timer:** Quick-cycle off timer (`Off`, `1 Hr`, `2 Hr`, `4 Hr`).
- **5-Step Down-to-Up Airflow Direction:**
  - Visual airflow indicator ordered cleanly from bottom to top: `DOWN` → `DOWN-MID` → `CENTER` → `UP-MID` → `UP`.
- **Crisp Haptic Feedback:**
  - Built-in **40ms hardware vibration** on every button tap for a physical remote feel.
- **Zero Bloat & 100% Offline:**
  - No internet access required, no trackers, no ads, and instant launch.

---

## 🧊 Supported INDcool AC Profiles

Tap the profile pill below the app title anytime to switch between the three built-in **INDcool** indoor unit profiles:

1. **INDcool Standard (Cool)** *(Default)* — Standard cool-only split inverter profile (`16°C – 30°C`).
2. **INDcool Pro (Full)** — Full-featured inverter profile with extended keycode and sleep support.
3. **INDcool Heat & Cool** — All-weather variant supporting both Cooling and Heating modes.

---

## 📱 Device Compatibility (Works with Phones Having an IR Blaster)

This app uses Android's native `ConsumerIrManager` API and **works exclusively on Android smartphones equipped with a built-in Infrared (IR) Blaster** (Android 8.0 Oreo / API 26 and above).

### Compatible Phone Brands & Series:
- **POCO:** POCO X6 / X6 Pro, POCO X5 / X5 Pro, POCO X4 Pro, POCO X3 / X3 Pro, POCO F6 / F5 / F4 / F3, POCO M6 / M5 / M4 series.
- **Xiaomi & Redmi:** Redmi Note 13 / 12 / 11 / 10 / 9 / 8 series, Redmi K-series, Xiaomi 14 / 13 / 12 / 11 series.
- **OnePlus:** OnePlus 12 / 12R, OnePlus 11 / 11R, OnePlus Open, OnePlus Nord CE 3 / Nord 3 / Nord 4.
- **Realme:** Realme GT 6 / GT 6T / GT Neo series, Realme Narzo 70 Pro / 60 Pro, Realme 12 Pro+ / 11 Pro+ (select IR models).
- **iQOO & Vivo:** iQOO 12 / 11 / Neo 9 Pro / Neo 7 Pro, Vivo X100 / X90 / V30 Pro (select IR models).
- **Oppo:** Oppo Reno 12 / 11 / 10 series, Oppo Find X7 / X6 series (select IR models).
- **Huawei / Honor:** Honor Magic / X-series & Huawei Mate / P-series models with top-mounted IR emitters.

> **Note:** Smartphones without a physical IR blaster hardware sensor (such as Samsung Galaxy S/A series, Google Pixel, Motorola, and Apple iPhones) cannot transmit infrared signals natively.

---

## 📥 Installation

1. Go to the [**Releases**](../../releases) section of this repository.
2. Download the latest **`INDcool-AC-Remote-v1.0.apk`**.
3. Open the downloaded `.apk` file on your IR-enabled Android phone.
4. If Google Play Protect prompts for confirmation, tap **More details** → **Install anyway**.
5. Point the top edge (IR emitter) of your smartphone toward your **INDcool AC** indoor unit and tap **POWER**.

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI Framework:** Android XML Views (`ConstraintLayout` / `LinearLayout` with Edge-to-Edge `WindowInsets` support)
- **Hardware APIs:** `android.hardware.ConsumerIrManager` & `android.os.Vibrator`
- **Minimum SDK:** Android 8.0 (API 26) | **Target SDK:** Android 15 (API 35)

---

<p align="center">
  <b>Made with ♥️ by CYNIDE</b>
</p>
