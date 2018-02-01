# Tutoriais
Tutoriais diversos

## Configurações para Cloudflare (plano free)
* **Remover admin bar:**

Adicionar isso no functions.php

```add_filter(‘show_admin_bar’, ‘__return_false’);```

* **Page rules:**

1.	\*__SEU_SITE__.com.br/wp-login\*

Security Level: High, Cache Level: Bypass	

2.	\*__SEU_SITE__.com.br/wp-admin\*

Cache Level: Bypass	

3.	\*__SEU_SITE__.com.br/\*

Always Online: On, Cache Level: Cache Everything	
