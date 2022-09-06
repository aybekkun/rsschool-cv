### CV
Aybek Amanbaev

---

### Contacts
* [Telegram](https://t.me/aaybekkun)
* [Facebook](https://www.facebook.com/amanbaevaybek)
* Phone: +998913809626
---

### About me:
Hi, my name is Aybek. I'm from Uzbekistan. I'm a frontend developer with 2 years experience. 

I am a talented, ambitious and hardworking individual, with broad skills and experience in digital and printed marketing, social media and leading projects.
Furthermore, I am adept at handling multiple tasks on a daily basis competently and at working well under pressure.

---

### Skills:
* HHTML&CSS
* React
* Wordpress
* Git&Github

---

### Language:
* English B1
* Russian

---

### Code example:

```
useEffect(() => {
    axios
      .get(/api/v1/products?limit=8&page=${currentPage})
      .then((res) => {
        setProducts(res.data.data);
        const totalPage = Math.ceil(Number(res.data.meta.total) / 8);
        setPageCount(totalPage);
      })
      .catch((error) => {
        console.log(error);
        alert("Нет данных");
      });
  }, [currentPage]);

  const handlePageClick = (e) => {
    setCurrentPage(e.selected + 1);
  };

```


