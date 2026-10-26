# 3D 世界 · 参天樱花树

Single-page Three.js scene with external CC0 PBR materials.

## Run locally

The page loads textures from `assets/`, so it must be served over HTTP (not opened as a `file://` URL).

The easiest way on Windows:

- Double-click `start-server.bat`
- It starts a local server and opens <http://127.0.0.1:8765/>

Or manually:

```powershell
cd "D:\deepseek haeshness工作区\3D世界\樱花树"
python -m http.server 8765 --bind 127.0.0.1
```

Open <http://127.0.0.1:8765/>.

Keep the server window open while using the scene.

## Assets

- `assets/bark/` — Bark Brown 02 (Poly Haven, CC0)
- `assets/soil/` — Brown Mud 02 (Poly Haven, CC0)
- `assets/sky/` — user-provided ember-dusk sky, mirrored seamless, no city/watermark
- `assets/petals/` — P2 sakura petal texture (1024, generated)
- `assets/grass/` — prairie grass ground + grass clump alpha (Poly Haven, CC0)
- See `assets/LICENSE.md` for source links and maps.
