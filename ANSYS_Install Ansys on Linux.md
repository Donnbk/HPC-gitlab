# Install Ansys Fluent on Cent Os ( Linux)

```c
sudo mkdir /mnt/iso 
sudo mount -o loop <image>.iso /mnt/iso
```

## Copy activate folder to ANSYS folder

```c
cp -r /home/donn/Downloads/shared_files /ANSYS2020R1/ansys_inc
```

## Run ANSYS

```c
cd /ANSYS2020R1/ansys_inc/v201/Framework/bin/Linux64/

./runwb2
```
