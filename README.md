# systest_moblin

Shared [systest](https://github.com/eerimoq/systest) utilities for the Moblin system test suites.

## Installation

```bash
pip install systest_moblin
```

## Modules

| Module | Contents |
| --- | --- |
| `systest_moblin.ffmpeg` | FFmpeg and ffprobe wrappers: recording, probing, volume and silence measurements, QR code and timecode reading. |
| `systest_moblin.test_case` | `TestCase`, a `systest.TestCase` with assertions on recorded video and audio. |
| `systest_moblin.utils` | `probe_recording()` and helpers on top of the FFmpeg wrappers. |
| `systest_moblin.web_server` | A static file web server as a context manager. |

`ffmpeg`, `ffprobe`, `zbarimg` and `ltcdump` must be installed and on the path.

## Release

Push a tag to publish to PyPI. The tag must match the version in `pyproject.toml`.

```bash
git tag 1.0.0
git push origin 1.0.0
```
