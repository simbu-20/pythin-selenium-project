TEST CASE 1
successful login panel 
#positive secenario

from selenium import webdriver
driver=webdriver.chrome
from selenium.webdriver.chrome.service import service as chromeservice
from selenium.webdriver.common.by import By
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername").send_keys('Admin')
driver.find_elemnt(By.ID,"txt password").send_keys("admin123")
driver.find_element(By.ID,"btnlogin").click()
act_title="OrangeHRM"
exp_title="orangeHRM"
if
  act_title==exp_title
  print("Login Test Passed")
else
  print("Login Test Failed")
driver.close()

NEGATIVE SECENARIOS

from selenium import webdriver
driver=webdriver.chrome
from selenium.webdriver.chrome.service import service as chromeservice
from selenium.webdriver.common.by import By
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername").send_keys('Admin')
driver.find_elemnt(By.ID,"txt password").send_keys("admin1234")
driver.find_element(By.ID,"btnlogin").click()
act_title="OrangeHRM"
exp_title="orangeHRM"
if
  act_title==exp_title
  print("Login Test Passed")
else
  print("Invalid password")
driver.close()

TEST CASE 2
 PIM MODULE 01:employee details
 
 from selenium import webdriver
driver=webdriver.chrome
from selenium.webdriver.chrome.service import service as chromeservice
from selenium.webdriver.common.by import By
from selenium.webdriver.select.support import select
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername").send_keys('Admin')
driver.find_elemnt(By.ID,"txt password").send_keys("admin123")
driver.find_element(By.ID,"btnlogin").click()
driver.find_element(BY.XPATH,"//class=[@button=button]".click()
driver.find-element(BY.XPATH,"//class=[@menuitem=name]".click()
driver.find_element(BY.XPATH,"//type=[@button=button]".click()
firstname='john'
driver.find_element(BY.XPATH,"//input=[@name='RESULT_Textfield-1']").send_keys(firstname)
print(firstname)
middle name=Henry
driver.find_element(BY.XPATH,"//input=[@name='RESULT_Textfield-2']").send_keys(middlename)
print(middlename)
last name=mathew
driver.find_element(BY.XPATH,"//input=[@name='RESULT_Textfield-3']").send_keys(lastname)
print(lastname) 
driver.find_element(BY.XPATH,"//class=[@button=submit]".click()
print(employee details sucessfully added)
driver.close()

PIM MODULE 02:exixting empolyee edit


from selenium import webdriver
driver=webdriver.chrome
from selenium.webdriver.chrome.service import service as chromeservice
from selenium.webdriver.common.by import By
from selenium.webdriver.select.support import select
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername").send_keys('Admin')
driver.find_elemnt(By.ID,"txt password").send_keys("admin123")
driver.find_element(By.ID,"btnlogin").click()
driver.find_element(BY.XPATH,"//type=[@button=button]".click()
driver.find-element(BY.XPATH,"//class=[@menuitem=name]".click()
diriver.find_element(BY.XPATH,"//div=[@class=data]".click()
driver.find_element(BY.XPATH,"//input=[@name='fname']".clear()
driver.find_element(BY.XPATH,"//input=[@name='fname']".send_keys('adcd')
driver.find_element(BY.XPATH,"//input=[@name='mname']".clear()
driver.find_element(BY.XPATH,"//input=[@name='mname']".send_keys('ef')
driver.find_element(BY.XPATH,"//input=[@name='lname']".clear()
driver.find_element(BY.XPATH,"//input=[@name='lname']".send_keys('gh')
driver.find_element(BY.XPATH,"//class=[@button=submit]".click()
print(employes details updated successfully)
driver.close()


PIM MODULE 03 Delete and exixting employee details


from selenium import webdriver
driver=webdriver.chrome
from selenium.webdriver.chrome.service import service as chromeservice
from selenium.webdriver.common.by import By
from selenium.webdriver.select.support import select
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername").send_keys('Admin')
driver.find_elemnt(By.ID,"txt password").send_keys("admin123")
driver.find_element(By.ID,"btnlogin").click()
driver.find_element(BY.XPATH,"//type=[@button=button]".click()
driver.find_element(BY.XPATH,"//class=[@menuitem=name]".click()
driver.find_element(BY.XPATH,"//class=[@trash=button]".click()
print(exsisting employee details deleted)
driver.close()
