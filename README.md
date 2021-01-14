Projeto para teste camplearning

Implementando Storage do Django para utilizar S3 (para arquivos estáticos)

---

1. Definir variáveis de credenciais da AWS, no arquivo testproject/settings.py
AWS_ACCESS_KEY_ID = '...'
AWS_SECRET_ACCESS_KEY = '...'
AWS_STORAGE_BUCKET_NAME = '...'

2. Sincronizar arquivos com S3
./manage.py collectstatic

3. Pronto. Rodar servidor para testar
./manage.py runserver
