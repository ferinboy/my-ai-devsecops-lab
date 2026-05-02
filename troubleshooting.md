1) bash: aider: command not found
แก้ไข โดยการพยายามลง aider ให้ตามที่ถาม chat gpt
pip install pipx
pipx install aider-chat
apt update
apt install python3-pip -y
pip install aider-chat
aider --model ollama/$MODEL \
  --no-auto-commits \
  --no-stream \
  --yes-always \
  --message "Write a Python one-liner that prints hello world"


2) Failed to build numpy==1.26.4
แก้ไข โดยการพยายามลง numpy ก่อนจะไปต่อ จำไม่ได้รันคำสั่งอะไร แต่มันติด error numpy ตัวนี้

