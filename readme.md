## horovod pytorch run script

horovodrun -np {num of gpu} python {youtfile.py}

## nvidia-smi per second

watch -n {second} -d nvidia-smi

## vscode-Remote SSH config 

Host 10.10.1.32:31675
    HostName 10.10.1.32  
    User svcapp
    Port 31675
