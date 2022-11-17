TEST CASE 1
successful login panel 
#positive secenario


from selenum import webdriver
from selenium.webdriver.chrome.service import service as chrome service
from seleneium.webdriver.common.by import By
driver.get("https://opensource-demo.orangehrmlive.com/web/index.php/auth/login")
driver.find_element(By.NAME,"txtusername).send_keys("Admin")
driver.find_elemnt(By.ID,"txt password").send_keys("admin123)
