# so-vits-svc-merge
<a target="_blank" href="https://colab.research.google.com/github/diontimmer/so-vits-svc-merge/blob/main/so_vits_svc_merge_v1.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Merge voice models to create brand new voices.

This simple function allows you to average the weights of two svc models creating a merged model and a (hopefully) awesome new voice.<br>
The ratio determines the amount of influence of model_b to model_a.

Model folders should be in the structure:<br>
<br>
**MODEL_FOLDER**<br>
└─── config.json<br>
└─── G_***.pth<br>
