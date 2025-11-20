# YOLOv11n Classification Model
Trained with Ultralytics YOLO under [GNU AGPL v3](LICENSE).

## Model
- File: `/content/runs/classify/train/weights/best.pt`
- Trained with:

  ```bash
  yolo classify train data=/content/data model=yolo11n-cls.pt epochs=10 imgsz=640
  ```
  
## License
This model is licensed under the GNU Affero General Public License v3.
The source code of the Ultralytics framework is available [here](https://github.com/ultralytics/ultralytics).

## Note
Training data is not provided as it is proprietary.
