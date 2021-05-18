****MultiviewImages_2_mesh3d****

1) Python Script which takes multiview rgb-d images in frame sequence and made 3d mesh out of it using python library OPen3d.
2) Secondly, it uses ICP Registeration to handle multiple images and align them in a way that makes 3d mesh accurately.
3) It takes two images of single frame first is RGB(".jpg") and second one is Depth(".png").
4) All frames cover object 360 degrees for better results.  


   **Setup**
           
           git clone https://github.com/MuhamadAlee/MultiviewImages_2_mesh3d.git
           pip install open3d==0.10.0
           python main__TSDF_Integrate__color_depth.py
