# my_package
exercise 3.1. ROBOTICS INTEGRATION Session 3. ROS Tools
what are the arguments of usb_cam-test.launch?
    <param name="video_device" value="/dev/video0" />   dispositiu de vídeo i el seu valor inicial (0)
    <param name="image_width" value="640" />    amplada imatge i el seu valor inicial (640)
    <param name="image_height" value="480" />   alçada imatge i el seu valor inicial (640)
    <param name="pixel_format" value="yuyv" />    format pixels i el seu valor inicial yuyv
    <param name="camera_frame_id" value="usb_cam" />    string que identifica la càmera usb_cam
    <param name="io_method" value="mmap"/>    mètode de sortida i valor mmap
    <param name="autosize" value="true" /> definició del tamany sortida, valor inicial autoformat.
