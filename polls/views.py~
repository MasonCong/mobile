from django.shortcuts import render
from django.core import serializers

# Create your views here.
from django.http import HttpResponse
from django.http import JsonResponse
 

def index(request):
    data={'cat':'https://s3.amazonaws.com/congstorage/picture/Cute-Cats-063.jpg',}   
    #return HttpResponse("Hello, world. You're at the polls index.")
    return JsonResponse(data)
