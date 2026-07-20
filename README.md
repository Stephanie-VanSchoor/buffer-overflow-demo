# buffer-overflow-demo

# 🛡️ Buffer Overflow en C - Démonstration

## 📌 Objectif
Ce projet montre une faille de **buffer overflow** et comment la protéger.

## 🔥 Compilation

### Version vulnérable
bash
gcc exploit.c -o exploit -fno-stack-protector -z execstack
