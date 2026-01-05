# Practical Deep Learning course | Training 100% working on Consumer GPUs via torch-directml on Windows OS
[Practical Deep Learning Course](https://github.com/fastai/fastbook) by [Jeremy Howard](https://github.com/jph00) (Big big thank you for creating the course and making it accessible to the whole world)

## Graphics card support
The **[torch-directml](https://pypi.org/project/torch-directml/)** expects DirectX12 which is supported on graphics cards from NVIDIA's Fermi architecture and later, AMD's GCN-based chips and later, Intel's Haswell and newer processors and Qualcomm Adreno 600 and later.

The table below shows the (theoretical) support matrix -

| Manufacturer | Supported Models |
|--------------|------------------|
| NVIDIA | GeForce GTX 600 series and newer |
| AMD | Radeon HD 7000 series and newer |
| Intel | Intel HD Graphics 5000 series and newer |
| Qualcomm | Qualcomm Adreno 600 and newer |

## Proof
> [Video Link](https://youtu.be/kWYTfiQvBws)

## Directions to properly use it
1. Clone the repo (learn some git if you don't know)
2. Open Command prompt/Powershell.
3. cd to the cloned repo. `practical_deep_learning_consumer_gpu`
4. `pip install -r .\requirements.txt`
5. Run the individual notebooks in your VSCode/Jupyter Server/IDEs

## Verify GPU Usage
1. In Windows 10 (version 1903 (10.0; Build 18362), and newer) or 11, Open **_Task Manager_**.
2. Go to **_Performance_** Tab. Select GPU (0 or 1 whichever was printed in 2nd cell of the notebook)
3. There will be 4 graphs. On the 2nd one (or any of them), click on the Dropdown item above the graph (in my case, it is _Copy_)
4. Select (**_Compute 0_** in Windows 10) OR (**1** in Windows 11). Watch the usage on the graph as the code is executed.
   
