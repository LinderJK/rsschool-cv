# [rsschool-cv](адрес "Описание")

## Slepchenkov Ilya

------------------
### About Me
I am 28 years old. I am currently working as a technical support engineer in the field of microelectronics.

------------------
### Contacts
- **Github** - https://github.com/LinderJK
- **Telegram** - LinderJk
- **Discord** - ilya Slepchenkov (@LinderJK)

------------------
### Skills

- HTML/CSS (Bootstrap, Material UI)
- JavaScript
- Git
------------------

### Code Example
```
    static send_json(url, data, chart) {
        document.body.classList.add('waiting');
        const xhr = new XMLHttpRequest();
        xhr.open('POST', url, true);
        xhr.onreadystatechange = function() {
            if (xhr.readyState === 4 && xhr.status === 200) {
                const json = xhr.responseText;
                Network.subscribe(url, json, chart);
            } else if (xhr.readyState === 4 && xhr.status !== 200) {
                window.alert('xhr.status = ' + xhr.status);
                document.body.classList.remove('waiting');
            } else {
                // document.body.classList.remove('waiting');
            }
        };
        xhr.send(data);
    }
```

