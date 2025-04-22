# DL_S25_Lora_Modification
In this project, we learn how to train LORA at different parameters to finetune existing Text Classification Model.
## 1. Sensitivity on Different Types of Bias
[bias_none.ipynb](./bias_none.ipynb)
[bias_lora_only.ipynb](./bias_lora_only.ipynb)
[bias_all.ipynb](./bias_all.ipynb)
Above are three files which runs individually under the different types of bias conditions.
And the comparison result is illustrated in [lora_bias_comparison](./lora_bias_comparison.png).

## 2. Sentivity on Rank and Lora Alpha
The result of analysis of different rank and lora alpha is presented in [heatmap_rank_lora_alpha](./combined_heatmaps.png).

## 3. Different Target Modules
To use LORA to finetune, we need to specify the target modules.
The training process of different target modules are shown in [different_target_modules.ipynb](./different_target_modules.ipynb)

## 4. Sentivity on Learning Rate
The training process of different learning rates are shown in [different_learning_rate.ipynb](./different_learning_rate.ipynb)
