# Level 2 Quiz

## User Story

Sebagai user saya bisa meng–input data yang digunakan untuk project quote.

## Acceptance Criteria

1.  Source code hanya terdiri dari html, css dan js file. Tidak diperbolehkan menggunakan library apapun kecuali react.js. Tidak diperbolehkan menggunakan framework (seperti next.js dan gatsby) atau frontend tool (seperti webpack, parcel dan vite). Tidak diperbolehkan juga menggunakan boilerplate, seperti CRA (create react app).

2.  Ikuti desain yang telah disediakan. Desain dapat diakses di https://www.figma.com/file/7JHVqENR3MQx6q3v4PhU5i/Multi-step-Form-(Community).

3.  Pada tahap pertama, user diminta untuk mengisi nama, email, no hp dan perusahaan. Setiap field wajib diisi, ketika user klik tombol “Next Step” dan ada field yang belum diisi maka tampilkan pesan error pada field yang belum diisi tersebut.

    1. Bonus: untuk field email dan no hp ditambahkan validasi format dengan ketentuan:

       1. email yang digunakan merupakan email yang disediakan oleh gmail, harus berakhiran “@gmail.com”, jika email tidak sesuai format maka tampilkan pesan error “Email is invalid”

       2. no hp harus diawali dengan “08” dan jumlah angka selanjutnya minimal 8 dan maksimal 12, jika no hp tidak sesuai format maka tampilkan pesan error “Phone number is invalid”

    2. Bonus: jika user klik tombol “Next Step” dan terdapat field yang memiliki pesan error maka atur fokus pada field tersebut. Cara atur fokus bisa dipelajari di https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/focus.

4.  Pada tahap kedua, user diminta untuk memilih salah satu servis yang terdiri dari “Development”, “Web Design”, “Marketing” dan “Other”. Pada tahap ini pilihan “Development” sudah langsung terpilih.

5.  Pada tahap ketiga, user diminta untuk memilih salah satu project budget yang terdiri dari “5000 - 10000”, “10000 - 20000”, “20000 - 50000” dan “50000 +”. Pada tahap ini pilihan “50000 +” sudah langsung terpilih.

6.  Pada tahap keempat, user diminta untuk mensubmit data yang sudah diinput sebelumnya. Saat user klik submit maka munculkan alert yang berisi data yang sudah diisi dan dikonversi menjadi string. Cara mengkonversi data menjadi string bisa dipelajari di https://www.w3schools.com/js/js_json_stringify.asp, sedangkan cara memunculkan alert bisa dipelajari di https://www.w3schools.com/jsref/met_win_alert.asp.

7.  Sebelum submit, user bisa melihat isian yang sudah diisi dari masing-masing tahap dengan mengklik tombol “Previous Step”.

8.  Tidak boleh menggunakan web store api, seperti localStorage dan sessionStorage.

## Submission

Silahkan kirimkan github link yang berisi source code dari website yang sudah dikerjakan ke https://forms.gle/tNq4zZTdZL7j1Eyx6. Lalu kirimkan juga video (yang menjelaskan bahwa sudah sesuai dg acceptance criteria) website yang sudah dikerjakan ke #nxn-level2-quiz atau #nxt-level2-quiz. Mohon kejujurannya untuk tidak melihat github peserta lain, semoga Allah menjaga kita untuk selalu bersikap jujur.
