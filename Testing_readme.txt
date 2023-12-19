-------------------------------------------------------------

To Create: 

Set the request type to POST.
Set the URL to "http://127.0.0.1:8000/api/notes/"
Set the request body to JSON with the note data 
{
    "title": "New Note",
    "content": "This is the content of the first note."
}

-------------------------------------------------------------

To Show All notes: 

Set the request type to GET.
Set the URL to "http://127.0.0.1:8000/api/notes/"

-------------------------------------------------------------

To Show note by an ID: 

Set the request type to GET.
Set the URL to "http://127.0.0.1:8000/api/notes/{id}"
Example: "http://127.0.0.1:8000/api/notes/1"

-------------------------------------------------------------

To Update note: 

Set the request type to PUT.
Set the URL to "http://127.0.0.1:8000/api/notes/{id}/"
Example: "http://127.0.0.1:8000/api/notes/1/"

-------------------------------------------------------------

To Delete note: 

Set the request type to DELETE.
Set the URL to "http://127.0.0.1:8000/api/notes/{id}/"
Example: "http://127.0.0.1:8000/api/notes/4/"

-------------------------------------------------------------
