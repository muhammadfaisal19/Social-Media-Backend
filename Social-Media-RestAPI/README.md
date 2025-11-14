
# ⭐ **A → Z MEAN Stack Dependencies (Short Definitions + Examples)**

---

## 🅰 **A**

### **axios**

*HTTP client to make API requests.*

```js
axios.get("/api/users");
```

### **@angular/router**

*Handles page navigation in Angular.*

```ts
RouterModule.forRoot(routes);
```

---

## 🅱 **B**

### **bcrypt**

*Hashes passwords securely.*

```js
bcrypt.hash("pass", 10);
```

### **body-parser**

*Parses incoming JSON (now built into Express).*

```js
app.use(express.json());
```

---

## 🅲 **C**

### **cors**

*Allows Angular to access Node/Express backend.*

```js
app.use(require("cors")());
```

### **compression**

*Gzip compression for faster responses.*

```js
app.use(compression());
```

---

## 🅳 **D**

### **dotenv**

*Stores environment variables in `.env`.*

```js
require("dotenv").config();
```

---

## 🅴 **E**

### **express**

*Main Node.js framework for API backend.*

```js
const app = express();
```

### **express-validator**

*Validates request data.*

```js
body("email").isEmail();
```

---

## 🅵 **F**

### **firebase** (optional)

*Used for hosting or push notifications.*

```js
import { initializeApp } from "firebase/app";
```

---

## 🅶 **G**

### **glob**

*Matches file paths.*

```js
glob("*.js", console.log);
```

---

## 🅷 **H**

### **helmet**

*Secures Express apps with HTTP headers.*

```js
app.use(helmet());
```

---

## 🅸 **I**

### **rxjs**

*Observables for Angular operations.*

```ts
observable.subscribe();
```

---

## 🅹 **J**

### **jsonwebtoken (JWT)**

*Creates & verifies login tokens.*

```js
jwt.sign({ id: 1 }, "secret");
```

---

## 🅺 **K**

### **karma**

*Angular's default testing tool.*

```bash
ng test
```

---

## 🅻 **L**

### **lodash**

*Utility functions for arrays/objects.*

```js
_.chunk([1,2,3,4], 2);
```

---

## 🅼 **M**

### **mongoose**

*MongoDB object modeling for Node.*

```js
mongoose.connect("mongodb://localhost/db");
```

### **multer**

*Handles file uploads.*

```js
upload.single("image");
```

### **morgan**

*HTTP request logger.*

```js
app.use(morgan("dev"));
```

---

## 🅽 **N**

### **nodemon**

*Auto-restarts the server on save.*

```bash
nodemon server.js
```

---

## 🅾 **O**

### **openapi / swagger-ui-express**

*API documentation tool.*

```js
app.use('/docs', swaggerUi.serve);
```

---

## 🅿 **passport**

*Authentication middleware.*

```js
passport.use(strategy);
```

### **primeNG**

*Angular UI component library.*

```ts
import { ButtonModule } from 'primeng/button';
```

---

## 🆀 **Q**

### **qs**

*Parses query strings.*

```js
qs.parse("?name=john");
```

---

## 🆁 **R**

### **rimraf**

*Deletes files or directories.*

```bash
rimraf dist/
```

---

## 🆂 **S**

### **socket.io**

*Real-time communication (chat, live updates).*

```js
io.on("connection", socket => {});
```

### **sass**

*CSS preprocessor for Angular styling.*

```scss
$color: blue;
```

---

## 🆃 **T**

### **typescript**

*Language used by Angular & MEAN backend.*

```ts
let x: number = 10;
```

---

## 🆄 **U**

### **uuid**

*Generates unique IDs.*

```js
uuid.v4();
```

---

## 🆅 **V**

### **validator**

*Validates inputs.*

```js
validator.isEmail("test@gmail.com");
```

---

## 🆆 **W**

### **winston**

*Professional logging.*

```js
winston.log("info", "message");
```

---

## 🆇 **X**

### **xml2js**

*Parses XML to JSON.*

```js
xml2js.parseString(xml);
```

---

## 🆈 **Y**

### **yargs**

*Builds CLI tools.*

```js
yargs.command("run", "Run script");
```

---

## 🆉 **Z**

### **zod**

*Schema validation.*

```js
z.string().parse("hello");
```

---

