## Tunacoder Featured Codes                                   [Next Page Golang Websites](https://carlamissiona.github.io/tunacoder/golang) 
I post my projects and preview of my sites here. I wrote some web development before and a lot of PHP. Now I write Python, Ruby and Golang. Pls. enjoy browsing my codes.


### Workclever in Django

[Visit The Site](https://worktrack.pythonanywhere.com/) on Pythonanywhere

![wrcklv](https://user-images.githubusercontent.com/1997542/185055395-4ad15ef5-9ab4-42dc-baa9-7502644d7cbe.png)


   ```
   # Configuring DJango Models
    class Company(models.Model):
      name = models.TextField(default='Company')
      date_modified = models.DateTimeField(auto_now_add=True)
      date_added = models.DateTimeField(auto_now_add=True)
      
   ```
It's easy to start a Django site. It will take time to configure it but everything will be easy since Django gives admin site with just a few configuration and a backend for your API.


```
from django.urls import include, path
from rest_framework import routers

from . import views 

router = routers.DefaultRouter()
router.register(r'company', views.CompanyViewSet)

# Wire up our API using automatic URL routing.
# Additionally, we include login URLs for the browsable API.
urlpatterns = [
    path('rest/', include(router.urls)),
    path('api-auth/', include('rest_framework.urls', namespace='rest_framework'))
] 
```
### Worktrack Features
- Job search
- Seeker applications
- Admin Configuration of Resume Template

### Ongoing work
1. Job seeker resume form
2. Company Who'll likely to hire


## Mixtapes
[Visit The Site](http://missionacarla.pythonanywhere.com/) on Pythonanywhere
 
Mixtapes is an online site which takes videos from vimeo api. The videos are hidden from frontend DOM. There's still a lot of work left in this project.

![django02](https://user-images.githubusercontent.com/1997542/185058999-45471d4d-75ec-4189-83d2-368d1d185ecf.png)




**[Golang Sites](https://carlamissiona.github.io/tunacoder/golang)**

