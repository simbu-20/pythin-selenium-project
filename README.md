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
  print("lLogin Test Failed")
driver.close()

