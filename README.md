
# API IBRP Website

API created to used at the main website IBPR(Iglesia Bautista Panambireta) 


## Documentation

[Documentation](https://github.com/rickyMelida/Api.IBPR.WebSite)

![example workflow](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)

## API Reference

#### User authentication verification

```http
  GET /api/auth/${uid}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `uid` | `string` | User uid provided by Firebase Auth |

#### Get all articles

```http
  GET /api/articles
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `None` | `-` | No Parameters |
| `id` | `integer` | Article id to get just one |

#### Get header verses

```http
  GET /api/GetHeaderVerses
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `None` | `-` | No Parameters |



