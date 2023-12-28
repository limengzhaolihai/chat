|-- undefined
    |-- decision-transformer-master
        |-- architecture.png
        |-- LICENSE.md
        |-- atari
        |   |-- conda_env.yml
        |   |-- create_dataset.py
        |   |-- fixed_replay_buffer.py
        |   |-- LICENSE
        |   |-- readme-atari.md
        |   |-- run.sh
        |   |-- run_dt_atari.py
        |   |-- mingpt
        |       |-- model_atari.py
        |       |-- trainer_atari.py
        |       |-- utils.py
        |       |-- __init__.py
        |-- gym
            |-- conda_env.yml
            |-- experiment.py
            |-- readme-gym.md
            |-- data
            |   |-- download_d4rl_datasets.py
            |-- decision_transformer
                |-- envs
                |   |-- reacher_2d.py
                |   |-- assets
                |       |-- reacher_2d.xml
                |-- evaluation
                |   |-- evaluate_episodes.py
                |   |-- __pycache__
                |       |-- evaluate_episodes.cpython-39.pyc
                |-- models
                |   |-- decision_transformer.py
                |   |-- mlp_bc.py
                |   |-- model.py
                |   |-- trajectory_gpt2.py
                |   |-- __pycache__
                |       |-- decision_transformer.cpython-39.pyc
                |       |-- model.cpython-39.pyc
                |       |-- trajectory_gpt2.cpython-39.pyc
                |-- training
                    |-- act_trainer.py
                    |-- seq_trainer.py
                    |-- trainer.py
