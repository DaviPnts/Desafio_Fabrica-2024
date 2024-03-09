![Captura de tela 2024-03-09 182550](https://github.com/DaviPnts/Desafio_Fabrica-2024/assets/162179470/eaacad12-9ce4-4d1d-b031-8769e4bb113f)
<h1>Desafio_Fabrica-2024</h1>
> Status = Developing ⚠️

### It's a project following a challenge, designed to catalog books.
## Some fields in main model are:

+ id_book
+ title
+ author
+ release_year
+ state
+ pages
+ publishing_company
+ creat_at (I'll change that)



## Some features that are allowed after cataloging a book and inserting the book url in insomnia are:

+ Post
+ Delete (if you want to use it again, you will need to catalog another book, and take the url)
+ Get
+ Patch
+ Put
+ Head
+ Options

## If you try to use the default Book List url, you will only be able to use:

+ Get
+ Post
+ Head
+ Options

## Some technologies used:

<table>
  <tr> 
   <td>Python</td>
   <td>Django</td>
   <td>DjangoFrameWork</td>
  </tr>
 <tr>
<td>3.11.8</td>
<td>5.0.3</td>
<td>3.14.0</td>
 </tr>
</table>

## How to to run the API: 

1) Activate venv (venv/Scripts/Activate);
2) Run the server (python manage.py runserver);
3) Go to the API ROOT link;
4) Since you go to the API ROOT site you click the "book/" link;
5) Use the id of some cataloged book or create another one, to be redirected to Book Instance (Example: http://127.0.0.1:8000/books//8870cc35-3772-47a1-a595-6f908b00fb1b/);
6) Now you have permission to use all the features (like DELETE or PATCH).

To be clear, it wasn't something I did entirely on my own, I needed help from gpt chat to find some errors and I watched a lot of video lessons. So there may be 70-80% similar codes. (but none of it was copied from gpt chat). 




