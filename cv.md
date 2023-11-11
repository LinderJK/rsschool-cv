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
------------------

### Education
- ***National Research University of Electronic Technology***

  Graduated from the Faculty of Microdevices and Technical Cybernetics (MPTK) in the direction of training development and operation of radio equipment.


- ***RsSchool «JavaScript/Front-end. Stage 0»***


------------------

### Languages

- English - B1
- Russian - Native
