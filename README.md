# Python version switching
>  為了能切換 Python 版本

下載 Anaconda
---
>  在 https://docs.anaconda.com/miniconda/install/，複製下載命令： curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe --output .\\Downloads\\Miniconda3-latest-Windows-x86_64.exe，在命令列輸入： curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe --output .\\Downloads\\Miniconda3-latest-Windows-x86_64.exe

安裝 Anaconda
---
>  執行下載的安裝檔：Miniconda3-latest-Windows-x86_64

執行 Anaconda Prompt
---
>  在 Windows 主選單，找到 Anaconda Prompt，點擊執行

執行 conda init
---
>  在 Anaconda Prompt，執行：conda init

安裝指定版本的 Python
---
>  若要安裝 Python 3.9版，在 Anaconda Prompt，執行：conda create -n py39 python=3.9 -y  

啟動指定版本的 Python
---
>  若要啟動 Python 3.9版，在 Anaconda Prompt，執行：conda activate py39

驗證所啟動的 Python 版本
---
>  若要驗證所啟動的 Python 版本，在 Anaconda Prompt，執行：Python

