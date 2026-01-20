# 🚀 Deploy Azure Virtual Machine using ARM Template

This lab demonstrates how to deploy a **Linux Virtual Machine** in Azure using an **ARM (Azure Resource Manager) template**.

---

## 🔹 Step 1: Create Resource Group
1. Go to Azure Portal
2. Search **Resource Groups**
3. Click **+ Create**
4. Name: `rg-arm-vm`
5. Region: `East US`
6. Click **Create**

---

## 🔹 Step 2: Upload ARM Template
1. Search **Deploy a custom template**
2. Click **Build your own template in the editor**
3. Paste content of `template.json`
4. Click **Save**

---

## 🔹 Step 3: Provide Parameters
- Resource Group: `rg-arm-vm`
- Admin Username: `azureuser`
- Admin Password: (as per parameters.json)

Click **Review + Create → Create**

---

## 🔹 Step 4: Verify Deployment
1. Go to **Virtual Machines**
2. Confirm VM status = **Running**
3. Note VM size: `Standard_B1s`

---

## 🔹 Step 5: Connect to VM
```bash
ssh azureuser@<PUBLIC-IP>
