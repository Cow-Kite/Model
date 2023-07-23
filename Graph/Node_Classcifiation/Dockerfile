FROM pytorch/pytorch:latest

WORKDIR /app

COPY . .

# 필요한 패키지 설치
RUN pip install torch-geometric torch torchvision

CMD ["python", "gcn.py"]
