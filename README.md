# Dashboard Gestion - Ventas e Inventarios

Dashboard para la gestión de ventas e inventarios en línea.

## Stack Tecnológico
- **Backend:** Django + Django REST Framework
- **Frontend:** React + TypeScript
- **Database:** PostgreSQL
- **Deployment:** Docker

## Estructura del Proyecto
```
Dashborad_Gestion-/
├── backend/
│   ├── manage.py
│   ├── requirements.txt
│   ├── config/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   └── apps/
│       ├── ventas/
│       └── inventario/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── services/
│   ├── public/
│   └── package.json
├── docker-compose.yml
└── .gitignore
```

## Instalación

### Backend
```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend
```bash
cd frontend
npm install
npm start
```

## Contribuciones
Por favor, consulta los issues para las tareas pendientes.
