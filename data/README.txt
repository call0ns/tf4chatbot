https://github.com/llSourcell/tensorflow_chatbot/issues/3
mkdir tensorflow_chatbot/data
cd tensorflow_chatbot/data
Get https://people.mpi-sws.org/~cristian/data/cornell_movie_dialogs_corpus.zip, put the *.txt files in this new data/ dir.
git clone https://github.com/suriyadeepan/datasets.git
Edit datasets/seq2seq/cornell_movie_corpus/scripts/prepare_data.py and uncomment the last lines so prepare_seq2seq_files executes.
python datasets/seq2seq/cornell_movie_corpus/scripts/prepare_data.py
This makes {train,test}.{enc,dec}

