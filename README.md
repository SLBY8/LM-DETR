# UAV-DEIM
	The implementation code for UAV-DEIM. The results file contains model weights.
# Environment
	conda create -n UAV-DEIM
	conda activate UAV-DEIM
	pip install -r requirements.txt
# Training
	CUDA_VISIBLE_DEVICES=0 python train.py
# Test
	python train.py -c configs/deim_dfine/deim_hgnetv2_n_coco.yml --test-only -r best_stg2.pth
# Aknowledgement
	UAV-DEIM is built upon DEIM https://www.shihuahuang.cn/DEIM/.
	This work is based on two public datasets: VisDrone and UAVDT.
	
