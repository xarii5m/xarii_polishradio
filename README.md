# xarii_polishradio
A FiveM resource that replaces GTA V’s default radio stations
with real Polish radio streams.

## ✅ | Features
- Replaces **7 default radio stations** with **real Polish** streams:

    -> RMF FM | Radio ESKA | Radio ZET | RMF MAXX | VOX FM | TOK FM | Radio Złote Przeboje
- Replaces the **default radio station logos** with **real Polish** ones
- Cleans up the radio wheel by **disabling unused stations**
- Fully **syncs volume** with GTA V’s native audio settings
- Implements **fallback URLs** for stream reliability
- Includes a **browser-based testing** interface
- Uses **Howler.js** for **efficient, cross-platform audio** streaming

## 📦 | Installation
1. **Download or clone** this repository into your ``resources`` folder
```
git clone https://github.com/yourusername/xarii_polishradio.git
```
2. **Add the resource** to your ``server.cfg``
```
ensure xarii_polishradio
```
3. **Restart** your server

## ⚙️ | Configuration
To add or edit radio stations, modify the ``fxmanifest.lua`` and insert lines like these:
```
supersede_radio 'original_radio_name'
supersede_radio_extra '{"url":"stream_url","volume":0.3,"name":"radio_name"}'
```
You can find a full list of GTA V's default radio station names in the ``data.js`` file.

# 🙏 | Thank you!
**Thank you** for using my script!
Feel free to **⭐ star** the repo or **contribute** if you'd like to improve it.
