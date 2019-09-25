#25-09-19-->Django class--> Creating Template directory

#Creating new directory with the name called "templates"
#TEMPLATE_DIR="template directory path"
#'DIRS': [TEMPLATE_DIR],
#create new file name in the templates with html extension
#later in views.py-->  
def mypage(request):
    return render(request,'intro.html')
#after that next goto urls.py--> 
path('mypage/',views.mypage,name="My Page"),
