# Natural languauge Processing(LIX001M05)_Project4, University of Groningen

# Team Members:
 1) Pooja Gowda S4410963
 2) Behrooz Nikandish S5035112
 3) Ayça Avcı S4505972


# You can find two directory as follows:
1) Experiment_replication
2) Experiment_direction
    a) Transformer models , 
    b) amount of data affect the learning of irregular past tense forms
    
       

# Steps to be added for following topics:
1)!pip install OpenNMT-py

2)!onmt_build_vocab -config config-exp1.yaml -n_sample 10000 

3)!onmt_train -config config-exp1.yaml

4)!onmt_translate -model experiment_1/run/model_step_1000.pt -src experiment_1/src_test.txt -output experiment_1/test-decoded.txt -gpu 0 -verbose -beam_size 12 

5)  import tensorboard
    %load_ext tensorboard
    %tensorboard --logdir logs
        



