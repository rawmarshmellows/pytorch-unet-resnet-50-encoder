# pytorch-unet-resnet-50-encoder

This model is a U-Net with a pretrained Resnet50 encoder. For most segmentation tasks that I've encountered using a pretrained encoder yields better results than training everything from scratch, though extracting the bottleneck layer from the PyTorch's implementation of Resnet is a bit of hassle so hopefully this will help someone!

You will need PyTorch version >= 0.3.0 and TorchVision version >= 0.2.0
