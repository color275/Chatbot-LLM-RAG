## Preparation in advance
- OpenSearch
- Bedrock
- IAM

## Env
create .env
```bash
OPENSEARCH_USERNAME=xxx
OPENSEARCH_PASSWORD=xxx
OPENSEARCH_ENDPOINT=search-xxx-xxxx.ap-northeast-2.es.amazonaws.com
```


```bash
python3.10 -m virtualenv venv
source ./venv/bin/activate
pip install -r requirements.txt
export AWS_DEFAULT_REGION='us-west-2'
streamlit run app.py --server.port 8501
```

## Img
![alt text](img/image01.png)