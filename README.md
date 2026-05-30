# 📺 HA TV Dashboard Blueprints

<p align="center">
  <strong>Home Assistant Blueprints for HA TV Dashboard</strong><br>
  <em>Turn your Android TV into a smart home command center!</em>
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=io.homeassistant.companion.androidtv">
    <img src="https://img.shields.io/badge/HA_TV_Dashboard-2026.2.1+-blue?style=for-the-badge&logo=android" alt="HA TV Dashboard">
  </a>
  <a href="https://www.home-assistant.io/">
    <img src="https://img.shields.io/badge/Home_Assistant-2024.6.0+-41BDF5?style=for-the-badge&logo=home-assistant&logoColor=white" alt="Home Assistant">
  </a>
</p>

---

> *Really these should have been made a long time ago, but better late than never* ¯\\_(ツ)_/¯

---

## 🚀 Get Started

Pick a Blueprint and press the button to add to Home Assistant, or paste the raw URL into:

**Settings → Automations & Scenes → Blueprints → Import Blueprint**

---

## 📜 Script Blueprints

| Blueprint | Description | Import |
|-----------|-------------|--------|
| 📹 **Stream Camera to TV** | Display camera feeds on your TV | [![Import][badge]][import-stream-camera] |
| 🚇 **Transit Status to TV** | Show transit line status updates | [![Import][badge]][import-transit] |
| 🌤️ **Weather to TV** | Display current weather conditions | [![Import][badge]][import-weather] |
| 🕐 **Time to TV** | Show current time on your TV | [![Import][badge]][import-time] |
| 📅 **Calendar Events to TV** | Display today's calendar events | [![Import][badge]][import-calendar] |
| 🔌 **Connection Status to TV** | Verify websocket connection | [![Import][badge]][import-connection] |

[badge]: https://my.home-assistant.io/badges/blueprint_import.svg
[import-stream-camera]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Fstream_camera_to_tv.yaml
[import-transit]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Ftransit_to_tv.yaml
[import-weather]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Fweather_to_tv.yaml
[import-time]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Ftime_to_tv.yaml
[import-calendar]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Fcalendar_todays_events_to_tv.yaml
[import-connection]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fscript%2Fconnection_to_tv.yaml

---

## ⚡ Automation Blueprints

| Blueprint | Description | Import |
|-----------|-------------|--------|
| 🚨 **Stream Camera on Trigger** | Auto-display camera when triggered (doorbell, motion, etc.) | [![Import][badge]][import-trigger] |

[import-trigger]: https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fnodinosaur%2Fha_tv_dashboard_blueprints%2Fblob%2Fmain%2Fautomation%2Fstream_camera_on_trigger_to_tv.yaml

---

## 🔗 Raw URLs

<details>
<summary>Click to expand raw URLs for manual import</summary>

### Script Blueprints
```
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/stream_camera_to_tv.yaml
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/transit_to_tv.yaml
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/weather_to_tv.yaml
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/time_to_tv.yaml
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/calendar_todays_events_to_tv.yaml
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/script/connection_to_tv.yaml
```

### Automation Blueprints
```
https://github.com/nodinosaur/ha_tv_dashboard_blueprints/blob/main/automation/stream_camera_on_trigger_to_tv.yaml
```

</details>

---

## 🔮 Coming Soon

- 🖼️ Image notifications
- ⚠️ Warning notifications

---

## 💡 Quick Tips

> **After importing:**
> 1. Go to **Scripts** (or **Automations** for automation blueprints)
> 2. Click **Create from blueprint**
> 3. Choose your HA TV blueprint
> 4. Fill in the fields and save!
>
> 🔄 *If scripts don't show immediately, go to **Developer Tools → YAML → Reload Scripts***

---

## ✅ Requirements

<a href="https://play.google.com/store/apps/details?id=io.homeassistant.companion.androidtv">
  <img src="https://img.shields.io/badge/Google_Play-HA_TV_Dashboard-green?style=for-the-badge&logo=google-play" alt="Get it on Google Play">
</a>

Requires **HA TV Dashboard 2026.2.1 (139)** or newer

---

## 📖 Documentation & Support

| Resource | Link |
|----------|------|
| 📚 **Wiki & Guides** | [View Wiki](https://github.com/nodinosaur/ha_tv_dashboard_wiki/wiki/HA-TV-Dashboard-about) |
| 🐛 **Issues & Features** | [GitHub Issues](https://github.com/nodinosaur/ha_tv_dashboard_wiki/issues) |
| 📧 **Email Support** | <a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#116;&#118;&#46;&#100;&#97;&#115;&#104;&#64;&#97;&#110;&#100;&#114;&#111;&#105;&#100;&#97;&#108;&#108;&#105;&#97;&#110;&#99;&#101;&#46;&#99;&#111;&#46;&#117;&#107;">&#116;&#118;&#46;&#100;&#97;&#115;&#104;&#64;&#97;&#110;&#100;&#114;&#111;&#105;&#100;&#97;&#108;&#108;&#105;&#97;&#110;&#99;&#101;&#46;&#99;&#111;&#46;&#117;&#107;</a> |

---

<p align="center">
  Made with ❤️ for the Home Assistant community by <a href="https://github.com/nodinosaur/">@nodinosaur</a>
</p>
