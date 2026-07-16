
| `ADMIN_PASSWORD` | `StrongPass!123` | Panel login password (min 8 chars, uppercase, lowercase, digits). |
| `SECRET_KEY` | `random_long_string` | Secret key used to sign JWT cookies. |
| `DOMAIN` | `sulgx.up.railway.app` | Your public domain. *Highly recommended for correct link generation.* |
| `DB_PATH` | `/data/panel.db` | Path for the SQLite database. **Important:** If your platform supports persistent volumes (see table below), mount a volume at `/data` to keep your data safe. |
| `PORT` | `8000` | (optional) The port your app listens on. Most platforms ignore this and use their own. |


---
