Samsung Galaxy S8 Korea variant (dreamltekor) KVM enabled test kernel
===========
This kernel is KVM enabled kernel for my test<br/>
You can build and use if you want<br/>
This kernel is for SM-G950N. (Galaxy S8 Korean variant)

### Fixes of kernel
* Virtualization, KVM enabled
* Add dtbtool for make boot.img

### How to build
1. Use `git submodule update --init --recursive` in the repository to import Android Image Kitchen.
2. Unpack original Galaxy S8 boot.img with `AIK-Linux/unpackimg.sh`. It will be extracted to `AIK-Linux/split_img/`.
3. Use `bash build_kernel.sh` to build kernel.
4. New boot.img will be created in `AIK_Linux/`

### Credits
* [Introduce Exynos dtbtool to the Linux build system](https://github.com/jcadduono/android_kernel_samsung_universal8895/commit/945a8df88cf1d783407a36b660e8c767634a1968)
