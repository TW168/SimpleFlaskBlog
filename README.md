# SimpleFlaskBlog
a simple blog post



============== SQLITE syntaxs ============================================
Blogpost.query.all()
Blogpost.query.all()[0].author

enter sqlite 
>python
>>>from app import db, Blogpost
>>>BlogPost.query.all()

create db
>python
>>>from app import db
>>>db.create_all()

add data to db
>python
>>> from app import Blogpost
>>> Blogpost.session.add(Blogpost(title='text', content='content', author='author'))
============== Setup ====================================================
C:\Users\tonyw\Documents\PythonApps\SimpleFlask\SimpleFlaskVenv\Scripts>
python -m venv SimpleFlaskVenv
got this from https://www.youtube.com/watch?v=3mwFC4SHY-Y
