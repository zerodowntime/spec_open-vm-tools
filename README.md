# open-vm-tools.spec

Spec file for build open-vm-tools rpm`s for centos 7

Building:
(using rpm-builder.sh https://github.com/zerodowntime/rpm-builder)

```
# git checkout <<branch>>
# rpm-build.sh \
#     -s <<spec_file>> \
#     -source <<included_source_dir>> \
#     -o <<output_rpm_dir>>

git checkout open-vm-tools-1.2
rpm-build.sh -s open-vm-tools.spec --source $(pwd)  -o $(pwd)/rpm
```
