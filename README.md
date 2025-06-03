# BCR_Final_1

Main Reference for SD Card Read/Write Module: https://blog.naver.com/PostView.naver?blogId=eziya76&logNo=221188701172&redirect=Dlog&widgetTypeCall=true&noTrackingCode=true&directAccess=false

## Hardware Needed

1. STM32F4 Discovery Microcontroller
2. [SD Card Module](https://linhkienchatluong.vn/module-doc-the-nho/module-doc-the-sd-card_sp497_ct206.aspx)
3. [MicroSD Kingston Class 10 32GB](https://cellphones.com.vn/the-nho-microsd-kingston-class-10-non-adapter-32gb.html) with [Adapter](https://tuanphong.vn/adapter-the-nho/adapter-microsd-to-sd)
Note: The MicroSD must be in FAT32 format.

## Hardware Connection

...

## Implementation

Step 1: Run the cifar10_validation_images_txt_generated.ipynb in Google Colab
- After running, the .ipynb file will generate 2 zip folders of "cifar10_essential" and "cifar10_full_dataset"
- Put all the cifar10_batch_1.txt, cifar10_batch_2.txt, ..., cifar10_batch_10.txt into the SD Card
