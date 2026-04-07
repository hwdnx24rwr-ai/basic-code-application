# Pople Amrutatylya Billing Desktop App

## Run the software

From `C:\Users\popla\OneDrive\Desktop\hotle billing`:

```powershell
npm start
```

## Build a downloadable Windows app

```powershell
npm run build
```

Build output will be created in:

```text
dist
```

You will get Windows build files such as:

- portable app
- installer (`nsis`)

## App pages

Use the desktop menu bar:

- `Billing > Admin`
- `Billing > Current Bill`
- `Billing > Manage Products`

## Main folders

- `app/pages`
  Edit the billing HTML pages here.
- `desktop`
  Edit the Electron desktop app wrapper here.
- `client`
  Future React frontend work.
- `server`
  Future MongoDB / API work.

## Notes

- This desktop app currently wraps the existing HTML-based billing system.
- Your data is still stored locally in the Electron app storage.
- The `client` and `server` folders are available if you want to continue upgrading this into a full React + MongoDB version later.
