# letsupgrade-python-b7
assignment day 2
#LIST DEFAULT FUNCTIONS# In[ ]:


#LIST DEFAULT FUNCTIONS


# In[1]:


# appand function


# In[2]:


a=["anjali","sai","sona","mohan"]


# In[3]:


a.append("ani")


# In[4]:


print(a)


# In[5]:


#entend function


# In[6]:


a=["anjali","sai","sona","mohan"]


# In[7]:


a.extend("bee")


# In[8]:


print(a)


# In[9]:


#count function


# In[10]:


a=["honeybee","bee","moth","fly"]


# In[12]:


print(a.count("bee"))


# In[11]:


print(a.count("honeybee"))


# In[13]:


print(a.count("honeybee"))
print(a.count("bee"))
print(a.count("moth"))
print(a.count(""))


# In[14]:


#reverse function


# In[15]:


a=[1,2,3,4,5,6]


# In[16]:


a.reverse()


# In[17]:


print(a)


# In[18]:


#pop function


# In[19]:


a.pop(1)


# In[20]:


a.pop()


# In[21]:


#dictionary functions


# In[26]:


dic={'an':'apple','b':'banana','c':'coconut'}


# In[30]:


dic


# In[31]:


dic.get('an')


# In[32]:


dic["b"]


# In[34]:


dic.keys()


# In[35]:


dic.pop('b')


# In[36]:


dic["d"]="anjali"


# In[37]:


dic


# In[38]:


dic.clear()


# In[39]:


dic


# In[1]:


# set and its default function


# In[2]:


set={1,2,3,4,5,6}


# In[3]:


print(set)


# In[4]:


set.add(7)


# In[5]:


print(set)


# In[7]:


set.remove(5)
print(set)


# In[8]:


set.pop()
print (set)


# In[9]:


set.clear()
print(set)


# In[10]:


a={12,34,65,87,66,65}
b={29,57,89,66,12,61}
print (a|b)
print(a.union(b))
print(a.intersection(b))


# In[11]:


#Tuple and its default function


# In[12]:


mytuple=('a',12.5,[1,2,3],"hello")
print(mytuple)


# In[13]:


print(type(mytuple))


# In[15]:


a,b,c,d=mytuple
print(a)
print(b)
print(c)
print(d)


# In[16]:


print (mytuple[0])


# In[17]:


print(mytuple[2][2])


# In[19]:


print(mytuple[-2])


# In[21]:


print(mytuple[1:3])


# In[22]:


del mytuple


# In[24]:


#String and its default functions


# In[30]:


str1 ="hello world"


# In[31]:


print(str1)


# In[32]:


str2=" to python"


# In[34]:


print(str1+str2)


# In[35]:


count=0
for letter in "hello world":
    if(letter=='l'):
        count+=1
        print(count,"letter found")


# In[36]:


'at'not in 'battle'


# In[37]:


'a'in 'program'


# In[38]:


str='cold'
print('len(str)=',len(str))


# In[ ]:





