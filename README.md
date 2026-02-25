# LLM
conda create -n xunjian python=3.10

pip install dashscope pyyaml   #依赖

# sk-ede645eb2ecb4ede99c8adce9f3b0f5e  阿里云密钥，没有就用我的

export DASHSCOPE_API_KEY="sk-你的实际API密钥"

python generate_inspection_plan.py
