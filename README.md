# Library-Manager
class library:
  def __init__(self):
   self.nobooks=0
   self.books=[]
  def addbook(self,book):
   self.books.append(book)
   self.nobooks=len(self.books)
  def showinfo(self):
    print(f"the library has {self.nobooks} books and they are:")
    for books in self.books:
     print(books)
l1=library()
l1.addbook("Harry Potter")
l1.addbook("The Great Gatsby")
l1.addbook("War and Peace")
l1.addbook("To Kill a Mockingbird")
l1.showinfo()
