# Ball-Following Sports Auto-Reframe

Players + ball detection/tracking, spatial analytics, and a 9:16 virtual camera that follows the ball.

```
pip install -r requirements.txt
python run.py --video input/clip.mp4
```

`run.py` regenerates this README and `performance_summary.md` from the measured results of your run
(speed, ball coverage, ball-in-crop %, jitter). Outputs land in `outputs/`.
Useful flags: `--out-size 720x1280`, `--ball-tiles 2 1`, `--ball-model my_ball.pt --ball-cls 0`, `--causal`, `--max-frames 120`.
