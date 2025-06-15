# Stokku

Inventory tracking system for Indonesian UMKM using React, Express, and WhatsApp API, featuring automated stock/expiry notifications to reduce loss and improve micro-enterprise sustainability.

## Table SQL

tb_items
| id | code_item | name |category| quantity | price|
| :- | :---------| :--- |:------|:-------- |:-------|
| `Int` | `string` `unique` | `string` |`int`| `int`| `int`|

tb_category
| id | name |  
| :-- | :------- |
| `Int`| `string` |

## 🌿 Branch Naming Example

```bash
| Type       | Utility                                              | Example                                     |
| ---------- | ---------------------------------------------------- | ------------------------------------------- |
| `feature`  | Added new features                                   | `feature/login-page`, `feature/invoice-api` |
| `fix`      | Fix bug                                              | `fix/cart-total`, `fix/login-error`         |
| `hotfix`   | Emergency repair in production                       | `hotfix/api-timeout`, `hotfix/logo-typo`    |
| `refactor` | Changes to code structure without functional changes | `refactor/auth-service`, `refactor/ui-form` |
| `chore`    | Minor routine/additional tasks                       | `chore/update-deps`, `chore/lint-config`    |
| `docs`     | Documentation changes                                | `docs/readme-update`, `docs/api-guide`      |
| `test`     | Testing additions/improvements                       | `test/login-validation`, `test/cart-flow`   |
```

## Authors

- [@pasteprosmana](https://www.github.com/mamsky)
- [@tajjudinaulia](https://github.com/Tajjahaadiin)
