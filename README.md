# 🛠️ Excel Root Cause Extractor – UiPath + Excel Automation

Automatically extract the **Root Cause** and **Solution** from outage incident descriptions using Excel formulas or UiPath workflows & AI.

---

## 📌 Use Case

Telecom and utility companies log incident reports in Excel with unstructured text. This automation identifies key information:

- **RootCause** – What caused the site to go down
- **Solution** – What action was taken to restore it

---

## ⚙️ Tools Used

- UiPath (optional for automation)
- Excel (regex-based formulas or VBA)
- AI content generation ( gimini 2.0 model )
- Example from telecom outage reports

---

## 📂 Project Structure

```plaintext
excel-rootcause-extractor/
├── Main.xaml                ← (UiPath workflow)
├── Outage_Example.xlsx      ← (Input sample)
├── README.md
```

---

## ✅ Sample Output

| Site ID   | Log Incident                                                              | RootCause         | Solution                            |
|-----------|---------------------------------------------------------------------------|-------------------|-------------------------------------|
| ID0001    | Site down due to AC failure and team replaced fan and site restored       |Ac fan failure     | Team replaced fan and site restored |
| ID0002    | Site down due to HCAC panel hanged we do Panel reset and site operational |HVAC panel hanged  | Panel reset and site operational    |

---

## 🔗 Author

👤 [Yamin Hassan (yshatory)](https://github.com/yshatory)
