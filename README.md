# Tutoriais
Tutoriais diversos

## Configurações para Cloudflare (plano free)
* **Remover admin bar:**

Adicionar isso no functions.php

```add_filter('show_admin_bar', '__return_false');```

* **Page Rules:**
Criar as seguintes configurações no Cloudflare, na sessão Page Rules. (Substituir \_\_SEU_SITE\_\_ pelo seu dominio)

| No. | URL | Opções |
| --- | --- | --- |
| 1.	| \*\_\_SEU_SITE\_\_.com.br/wp-login\* | Security Level: High, Cache Level: Bypass |
| 2.	| \*\_\_SEU_SITE\_\_.com.br/wp-admin\* | Cache Level: Bypass |
| 3.	| \*\_\_SEU_SITE\_\_.com.br/\* | Always Online: On, Cache Level: Cache Everything	|
