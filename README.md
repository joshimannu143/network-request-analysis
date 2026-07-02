# 🌐 Network Requests Analysis

## 📌 Website Visited
**URL:** https://shorterloop.com

---

## 📡 Network Requests

### 1. GET /
- **Type:** Document
- **Status Code:** `200 OK`
- **Header:** `Content-Type: text/html; charset=utf-8`

**Description:**
This is the main HTML document of the website. It is the first file requested by the browser when the webpage is opened.

---

### 2. GET /assets/scripts/lozad.min.js
- **Type:** Script
- **Status Code:** `200 OK`
- **Header:** `Content-Type: text/javascript; charset=utf-8`

**Description:**
This JavaScript file is responsible for efficient content loading and lazy loading of website resources.

---

### 3. GET /assets/css/fonts.css
- **Type:** Stylesheet
- **Status Code:** `200 OK`
- **Header:** `Content-Type: text/css; charset=utf-8`

**Description:**
This stylesheet contains the font definitions used throughout the website.

---

### 4. GET /assets/css/main.css
- **Type:** Stylesheet
- **Status Code:** `200 OK`
- **Header:** `Content-Type: text/css; charset=utf-8`

**Description:**
This file provides the primary styling, layout, and visual appearance of the website.

---

### 5. GET /assets/fonts/geist-sans/Geist-Regular.woff2
- **Type:** Font
- **Status Code:** `200 OK`
- **Header:** `Content-Type: font/woff2`

**Description:**
This font file is downloaded by the browser to display text using the Geist font family.

---

# 🌍 DNS Lookup

## Command Used

```bash
nslookup shorterloop.com
```

## Output

```text
Server:  UnKnown
Address: 10.146.168.49

Non-authoritative answer:
Name:    shorterloop.com
Address: 199.36.158.100
```

**Explanation:**

The DNS lookup resolves the domain name **shorterloop.com** into its corresponding IP address (**199.36.158.100**), allowing the browser to establish a connection with the website's server.

---

# 📷 Screenshots

| Screenshot | Description |
|------------|-------------|
| **network.png** | Network tab showing all requests generated while loading the website. |
| **terminal.png** | Output of the `nslookup` command displaying the resolved IP address. |

---

# 📖 What I Learned

- A webpage is composed of multiple resources such as **HTML, CSS, JavaScript, fonts, and images**.
- The browser sends **individual HTTP requests** for each resource required to render the webpage.
- **DNS (Domain Name System)** translates a domain name into an IP address so that the browser can locate the server.
- A **200 OK** status code indicates that the requested resource was successfully delivered by the server.
- **Response headers** provide important information about the returned resource, including its content type and encoding.

---

## 📝 Conclusion

Analyzing the network activity of **https://shorterloop.com** helped in understanding how modern websites are loaded. Every webpage consists of multiple resources requested independently by the browser. The DNS lookup demonstrated how a domain name is translated into an IP address before communication begins. This exercise provided practical knowledge of HTTP requests, response headers, status codes, and the role of DNS in web communication.
