# Syscalls Per API

The following table shows 10 example APIs for OpenCV and the corresponding syscalls they use.

| **API**                                  | **Syscalls**                      |
|------------------------------------------|-----------------------------------|
| imread()                                 | openat fstat read brk close lseek |
| cvLoadImage()                            | openat mmap fstat read lseek      |
| cv::CascadeClassifier::CascadeClassifier | fstat read lseek brk close openat |
| cv::CascadeClassifier::load              | openat fstat read lseek brk close |
| cv::CascadeClassifier::read              | openat fstat read lseek brk close |
| cv::FileStorage                          | openat fstat read lseek brk close |
| cv::VideoCapture::VideoCapture           | openat close ioctl mmap           |
| cv::VideoCapture::operator>>             | ioctl select brk                  |
| cv::VideoCapture::get                    | ioctl                             |
| cv::VideoCapture::open                   | openat ioctl mmap brk             |
