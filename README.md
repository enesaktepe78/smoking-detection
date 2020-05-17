# smoking-detection
 
 Require Python 3.6+ installed.
 
 To install the CPU-only version of TensorFlow, enter the following command.
 
  C:\> pip install --upgrade tensorflow==1.15.2
  
  Clone the Object detection tensorflow gitub repository by going to this link [TensorFlow's Object Detection API] (https://github.com/tensorflow/models).
  
  => Install the following through pip install command.

pip install pillow

pip install lxml

pip install jupyter

pip install matplotlib

pip install pandas

pip install opencv-python


Step 4:
  => Protobuf Compilation:

The Tensorflow Object Detection API uses Protobufs to configure model and training parameters. Before the framework can be used, the Protobuf libraries must be compiled. This should be done by running the following command from the tensorflow/models/research/ directory:

  => From tensorflow/models/research/ folder in command line run the below command.

protoc object_detection/protos/*.proto --python_out=.

  => If you are getting error in running the above then run the above command for individual .proto files one by one in that location as follows: protoc object_detection/protos/anchor_generator.proto --python_out=.

Step 5:

=> Download my repository and extract into models/research/object_detection

Step 6:

download the model https://drive.google.com/file/d/1V1XYn7CmYZfVgEvH3zor5o0RdRZ7jMKs/view and extract into "cigarette" file

Step 7:

Open models/research/object_detection with PyCharm



