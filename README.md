# **Angular CRUD Application with Angular Material and JSON Server**  

## **Project Overview**  
This project is a **CRUD (Create, Read, Update, Delete)** application built with:  
- **Angular** (Frontend Framework)  
- **Angular Material** (UI Component Library)  
- **JSON Server** (Mock REST API for development)  

It demonstrates basic operations for managing data, such as adding, viewing, editing, and deleting records.

---

## **Features**  
✔ **Create**: Add new records  
✔ **Read**: Fetch and display records  
✔ **Update**: Modify existing records  
✔ **Delete**: Remove records  
✔ **Responsive UI**: Built with Angular Material for a clean and modern look  
✔ **Mock Backend**: JSON Server simulates a REST API  

---

## **Prerequisites**  
Before running the project, ensure you have:  
- **Node.js** (v14 or later)  
- **npm** (or **yarn**)  
- **Angular CLI** (Install via `npm install -g @angular/cli`)  

---

## **Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### **2. Install Dependencies**  
```bash
npm install
```

### **3. Run JSON Server (Mock API)**  
Start the JSON server to simulate a backend:  
```bash
json-server --watch db.json
```
The server will run on `http://localhost:3000` by default.  

### **4. Run the Angular Application**  
In a separate terminal, start the Angular app:  
```bash
ng serve
```
The app will be available at `http://localhost:4200`.  

---

## **Available Scripts**  
| Command | Description |
|---------|-------------|
| `npm start` | Runs Angular app (`ng serve`) |
| `json-server --watch db.json` | Starts JSON Server |
| `npm run build` | Builds Angular for production |
| `npm test` | Runs Angular tests |

---

## **Customization**  
### **Modifying the Mock Data**  
Edit `db.json` to change the mock API data:  
```json
{
  "productList": [
    {
      "productName": "Kashmiri Apples", "category": "Fruits", "date": "2025-03-19T18:30:00.000Z", "freshness": "Second Hand", "price": 900, "comment": "Exclusive apples from kashmir.", "id": "eb28"
    },
    {
      "productName": "Custard apple", "category": "Fruits", "date": "2025-04-17T18:30:00.000Z", "freshness": "Brand New", "price": 69, "comment": "Garmi ka dushman, Sardi ka dost !!!", "id": "9e35"
    },
}
```

### **Adding New Features**  
1. **New Components**: Generate with `ng generate component component-name`  
2. **New Services**: Generate with `ng generate service service-name`  
3. **New Models**: Define interfaces in `src/app/models/`  

---

## **Troubleshooting**  
- **Port Conflicts**: If `3000` (JSON Server) or `4200` (Angular) is busy, change the port:  
  ```bash
  ng serve --port 4201  # For Angular
  json-server --watch db.json --port 3001  # For JSON Server
  ```
- **Missing Dependencies**: Run `npm install` if any errors occur.  

---

## **Contributing**  
Feel free to fork, improve, and submit pull requests!  

---

**Happy Coding! 🚀**
