# Authentication

---

### 1. `useSearchParams()` nima ?

**url parametrini boshqarish imkonini beradi. Yani 'http://localhost:3000/auth?mode=login' soroq qismidan keyingi qismlar bilan ishlashda**

### 2. `searchParams.get("mode")`

**urldagi key orqali valueni olish uchun kerak**
**Misol:**

```jsx
  const [searchParams] = useSearchParams();
  const isLogin = searchParams.get("mode") === "login";
```


