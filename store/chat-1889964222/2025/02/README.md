# February 2025 - 🐊 IT. Archivium - Uuuuuuuuuu-u

[🐊 IT. Archivium - Uuuuuuuuuu-u](../../)



---

### Post 700

 
![700-photo.jpg](700-photo.jpg) 




2025-02-27 - 21:08:20


🗂 file: [700-photo.jpg](700-photo.jpg) 






---

### Post 699




document.addEventListener(&quot;DOMContentLoaded&quot;, function () {<br />    const form = document.querySelector(&quot;.signupform&quot;);<br />    if (!form) return;<br /><br />    form.querySelector(&quot;#fitem_id_username .col-form-label&quot;).innerHTML = &quot;E-mail&quot;;<br /><br />    const usernameInput = form.querySelector(&quot;#id_username&quot;);<br />    const emailInput = form.querySelector(&quot;#id_email&quot;);<br />    const email2Input = form.querySelector(&quot;#id_email2&quot;);<br /><br />    if (usernameInput &amp;&amp; emailInput &amp;&amp; email2Input) {<br />        usernameInput.addEventListener(&quot;input&quot;, function () {<br />            emailInput.value = this.value;<br />            email2Input.value = this.value;<br />        });<br />    }<br /><br />    // Скрытие ненужных элементов<br />    [&quot;#fitem_id_email&quot;, &quot;#fitem_id_email2&quot;, &quot;#fitem_id_country&quot;, &quot;#fitem_id_city&quot;]<br />        .forEach(selector =&gt; {<br />            const element = form.querySelector(selector);<br />            if (element) element.style.display = &quot;none&quot;;<br />        });<br /><br />    // Обновление лейблов и плейсхолдеров<br />    const labels = {<br />        &quot;#id_firstname_label&quot;: &quot;Имя и Отчество (Name and Patronymic)&lt;br&gt;[Дмитрий Александрович]&quot;,<br />        &quot;#id_lastname_label&quot;: &quot;Фамилия (Last name)&lt;br&gt;[Петров]&quot;<br />    };<br />    for (const [selector, text] of Object.entries(labels)) {<br />        const label = form.querySelector(selector);<br />        if (label) label.innerHTML = text;<br />    }<br /><br />    const placeholders = {<br />        &quot;#id_firstname&quot;: &quot;Имя Отчество&quot;,<br />        &quot;#id_lastname&quot;: &quot;Фамилия&quot;<br />    };<br />    for (const [selector, text] of Object.entries(placeholders)) {<br />        const input = form.querySelector(selector);<br />        if (input) input.placeholder = text;<br />    }<br /><br />    // Упрощение стилей для .fdate_selector<br />    const dateSelector = form.querySelector(&quot;.fdate_selector&quot;);<br />    if (dateSelector) {<br />        dateSelector.style.flexWrap = &quot;wrap&quot;;<br />        <a href="dateSelector.style.gap">dateSelector.style.gap</a> = &quot;1rem&quot;;<br />    }<br /><br />    // Hide Element on lostforgot page<br />    const forgotFormUsername = document.querySelector(&quot;#id_searchbyusername&quot;);<br />    if (forgotFormUsername) forgotFormUsername.style.display = &quot;none&quot;;<br /><br />});


2025-02-25 - 17:29:36







---

### Post 698




qw with comment or none


2025-02-21 - 02:03:39







---

### Post 697




<a href="https://wakatime.com">https://wakatime.com</a>


2025-02-19 - 02:13:21







---

### Post 696




async def construct_text_summary(summary: dict):<br />    all_rows = []<br />    for chapter in summary.get(&#x27;chapters&#x27;):<br />        chapter_time = chapter.get(&#x27;startTime&#x27;)<br />        chapter_title = chapter.get(&#x27;content&#x27;)<br />        title_html = f&#x27;&lt;b&gt;{chapter_time} - {chapter_title}&lt;/b&gt;&#x27;<br />        theses = [&#x27; • &#x27; + thesis.get(&#x27;content&#x27;) for thesis in chapter.get(&#x27;theses&#x27;)]<br />        rows = [title_html] + theses + [&#x27;&#x27;]<br />        all_rows += rows<br /><br />    return &#x27;\n&#x27;.join(all_rows)


2025-02-19 - 00:29:29







---

### Post 695




Choose one of these options. <br />Exit in seconds: 8


2025-02-17 - 03:28:21







---

### Post 694




<a href="https://youtu.be/8NZuyitYCwI?si=90sNC-3e_QnL_hSq">https://youtu.be/8NZuyitYCwI?si=90sNC-3e_QnL_hSq</a>


2025-02-17 - 03:28:21







---

### Post 693

 
![693-thumbnail.jpg](693-thumbnail.jpg) 



Мой пет-проект спустя год учебы на программиста<br /><a href="http://youtu.be/43hci8QsHSg">youtu.be/43hci8QsHSg</a> [11:41]<br />Идущий к IT


2025-02-04 - 12:44:37


🗂 file: [693-audio.m4a](693-audio.m4a) 






---

### Post 692




⏳ Preparing...


2025-02-04 - 12:43:22







---

### Post 691




<a href="https://youtu.be/43hci8QsHSg?si=1pTk3GHF6wUnf0Bs">https://youtu.be/43hci8QsHSg?si=1pTk3GHF6wUnf0Bs</a>


2025-02-04 - 12:43:22





