#テーブル設計

## users table
| Colum              | Type    | Option                    |
| ------------------ | ------- | ------------------------- |
| email              | string  | null: false, unique: true |
| encrypted_password | string  | null: false               |
| nickname           | string  | null: false               |
| first_name         | string  | null: false               |
| last_name          | string  | null: false               |
| first_name_ruby    | string  | null: false               |
| last_name_ruby     | string  | null: false               |

