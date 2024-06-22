This is the reository for a operating system built on rust.
First Install Rust.
Second install cargo packages
Thired install qemux86 model
Add the cargo path to your environmet variable.
Run cargo build
Run cargo bootimage
Run qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin
# NexOS
