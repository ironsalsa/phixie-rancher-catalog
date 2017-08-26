      secrets:
        - otb_database_name
        - otb_database_user
        - otb_database_password
        - otb_wordpress_user
        - otb_wordpress_pass

secrets:
  otb_database_name:
    external: true
  otb_database_user:
    external: true
  otb_database_password:
    external: true
  otb_wordpress_user:
    external: true
  otb_wordpress_pass:
    external: true

      environment:
        WORDPRESS_DATABASE_NAME: /run/secrets/otb_database_name
        WORDPRESS_DATABASE_USER: /run/secrets/otb_database_user
        WORDPRESS_DATABASE_PASSWORD: /run/secrets/otb_database_password
        WORDPRESS_USERNAME: /run/secrets/otb_wordpress_user
        WORDPRESS_PASSWORD: /run/secrets/otb_wordpress_pass