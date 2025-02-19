Создать ключ ssh

ssh -keygen -t ed25519 -C "почта"
ls ~/.ssh
cat ~/.ssh/id_edu25519.pub

Добавить клюс в ssh агента

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_eg25519



