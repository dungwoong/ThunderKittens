## Running the attention demo
Go to kernels/attn/demo

```bash
make GPU=4090 # or H100
python3 gentests.py
<target> randn_2048_128.txt
```