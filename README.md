# TailwindCSS Starter Pack

## **How To start**

### **Clone From:**

```
git clone https://github.com/ibnshayed/TailwindCSS-Starter-Pack.git 
```

### **Build:**

```
npm run dev
```

### **Start: On VS Code any live server**

## **How to Create this**

```
npm init -y
npm i tailwindcss@latest postcss-cli@latest autoprefixer@latest
```

### Tailwind Full Config

```
npx tailwind init --full ( change name to tailwind-default.config.css )
```

### Tailwind & Postcss Config

```
npx tailwind init -p
```

# package.json

```javascript
"scripts": {
    "dev": "set TAILWIND_MODE=watch&postcss src/css/tailwind.css -o src/css/styles.css -w --verbose",
    "build": "NODE_ENV=production postcss src/css/tailwind.css -o src/css/styles.css -m"
  }
```
