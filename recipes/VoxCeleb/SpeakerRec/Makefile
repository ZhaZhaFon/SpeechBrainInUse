


train-8k:
#	python3 ./config_train_encoder.py ./hparams/config_train_ecapa_8k.yaml
#	python3 ./train_speaker_embeddings.py ./hparams/config_train_ecapa_8k.yaml
	python3 ./config_train_encoder.py ./hparams/config_train_ecapa_8k.yaml


### x-vector

#train:
#	python3 ./config_train_speaker_embeddings.py ./hparams/config_train_x_vectors.yaml

### x-vector ###
train-xvector:
	python3 ./config_train_encoder.py ./hparams/config_train_xvector.yaml
eval-xvector:
	python3 ./config_eval_plda.py ./hparams/config_eval_xvector.yaml

### ecapa-tdnn ###
train-ecapa:
	python3 ./config_train_encoder.py ./hparams/config_train_ecapa.yaml
eval-ecapa:
	python3 ./config_eval_cosine.py ./hparams/config_eval_ecapa.yaml

### epoch ###
# epoch = 20
train-epoch20:
	python3 ./config_train_encoder.py ./exp_hparams/ecapa_epoch20.yaml

