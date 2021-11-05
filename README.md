# Getting Started

```
cd $CHIPYARD_PATH/software/firemarshal/example-workloads
git clone https://github.com/KingFrige/run-hello-workload.git

cd $CHIPYARD_PATH/software/firemarshal
./marshal -v build example-workloads/run-hello-workload/marshal-configs/run-hello.json
./marshal -v launch example-workloads/run-hello-workload/marshal-configs/run-hello.json



guestmount --pid-file guestmount.pid -a images/run-hello.img -m /dev/sda disk-mount

ll disk-mount
```

# ref

[firemarshal](https://github.com/firesim/FireMarshal)
