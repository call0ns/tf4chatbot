# tf4chatbot

based on source code from Sirajology. (adapt 4 tf1.0 and ECS)
https://github.com/llSourcell/tensorflow_chatbot.git

## training
python execute.py --mode=train --train_enc=data/train.enc --train_dec=data/train.dec --test_enc=data/test.enc --test_dec=data/test.dec --working_directory=working_dir --enc_vocab_size=20000 --dec_vocab_size=20000 --layer_size=256

## test
python execute.py --mode=test --train_enc=data/train.enc --train_dec=data/train.dec --test_enc=data/test.enc --test_dec=data/test.dec --working_directory=working_dir --enc_vocab_size=20000 --dec_vocab_size=20000 --layer_size=256

