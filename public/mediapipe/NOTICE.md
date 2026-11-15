# Body-tracking files

These files let the Movement check follow body landmarks in the browser. They are committed so a deployed copy of OrbitWell has full body tracking without a setup step.

| File | Source | Licence |
|---|---|---|
| `vision_bundle.mjs`, `wasm/` | npm package `@mediapipe/tasks-vision` 1.2.3 | Apache License 2.0 |
| `pose_landmarker_lite.task` | Google MediaPipe model storage (`pose_landmarker_lite`, float16) | Apache License 2.0 |

Licence text: https://www.apache.org/licenses/LICENSE-2.0

Everything runs in the browser. No video or image leaves the device. To refresh these files, run `npm run setup:pose -- --yes` (see `docs/pose-setup.md`).
