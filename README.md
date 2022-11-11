# pypi_project_nums_primos

```
from wbs import WDShorcuts
service = Service(ChromeDriverManager().install())
driver = webdriver.Chrome(service=service)
ddriver = WDSShorcuts(driver)

select_based = ddriver.webdriverwait_el_by(
    By.CSS_SELECTOR, '[data-baseweb="select"]')
ddriver.send_keys_anywhere(Keys.TAB)
# and much more
```
