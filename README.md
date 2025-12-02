# Note

Aplicação simples para criação e organização de anotações. Permite editar o perfil do usuário e personalizar as cores das notas.

<p align="center">
  <img src="https://user-images.githubusercontent.com/54549125/152058253-b6b80bf9-3b04-4d14-a00f-92acd528d563.gif" height="400"/>
</p>

## Descrição

O Note foi desenvolvido do zero, sem uso de frameworks, seguindo o padrão MVC para manter o código organizado.  
A aplicação possui um sistema de recuperação de senha e um componente de log próprio, responsável por registrar acessos indevidos ou erros, notificando automaticamente via bot no Telegram.

## Funcionamento

As notas podem ser criadas, editadas, excluídas e organizadas por cores. O usuário também pode alterar informações do seu perfil. Todas as operações são simples e diretas, com foco na usabilidade.

## Colocando para funcionar

Para testar o projeto localmente:

- Crie uma pasta chamada **cache** dentro da pasta `source`
- Crie o arquivo `app.php` dentro da pasta `config` usando como base o arquivo `app.sample.php`

## License

Note is open-sourced software licensed under the [MIT license](LICENSE).
