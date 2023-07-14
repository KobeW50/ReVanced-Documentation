## About Revancify
Revancify is a tool for building ReVanced on termux.

The developer of Revancify is [@decipher3114](https://github.com/decipher3114), visit the [Revancify repository](https://github.com/decipher3114/Revancify) for more info.

#### How to install Revancify for the first time
1. Firstly, you have to install Termux. Install it from [F-Droid](https://f-droid.org/packages/com.termux/).

2. After that, you have to run these commands:

```
pkg update -y && pkg install git -y && git clone https://github.com/decipher3114/Revancify.git && ./Revancify/revancify
```

#### Usage
After installation, type `revancify` in termux and press enter.  
   
Or use with arguments. Check them with `revancify -h` or `revancify --help`  


## Guide with screenshots
0. If you are installing Revancify for the first time, you can select the source.

![1](https://user-images.githubusercontent.com/108592928/221589836-a061aa72-7af2-47ca-b83c-4efa7184a722.png)

Use the `space` key to select `inotia00`.

1. Select `4 Update Resources` to download the latest patch.

![2](https://user-images.githubusercontent.com/108592928/221590174-ce8e406f-5fad-4990-a26c-214a5cec7dd2.png)

2. You can select patches to include or exclude through `2 Select Patches`.

![3](https://user-images.githubusercontent.com/108592928/221591977-447ff291-5738-419d-bd78-1479da3750c7.png)

If you are patching in a ROOT environment, you should exclude the `microg-support` patch.

If you are patching in a NON-ROOT environment, you should include the `microg-support` patch.

![4](https://user-images.githubusercontent.com/108592928/221592020-50b71f53-8064-461f-8603-6ac596e29793.png)

3. Before starting the patch, Please read this [documentation]( https://github.com/inotia00/revanced-documentation/wiki/Before-start-(Prerequisites)#common)

4. Select `1 Patch App`

![5](https://user-images.githubusercontent.com/108592928/221592758-f54983c3-5046-43a1-b2b5-8cfd7a8b8573.png)

From the Version Selection Menu, choose the version labeled '[SUPPORTED]'.

![6](https://user-images.githubusercontent.com/108592928/221592769-62cdb522-cdb0-44f0-a40a-a5809dfddde4.png)

The patch will automatically proceed and prompt you t install after patching is complete.