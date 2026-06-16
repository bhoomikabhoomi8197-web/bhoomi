# bhoomi
# # bhoom
# 🌐 Service Accounts and Roles: Fundamentals || GSP199 🚀 [![Open Lab](https://img.shields.io/badge/Open-Lab-blue?style=flat)](https://www.skills.google/games/7173/labs/44429)

## ⚠️ Disclaimer ⚠️

<blockquote style="background-color: #fffbea; border-left: 6px solid #f7c948; padding: 1em; font-size: 15px; line-height: 1.5;">
  <strong>Educational Purpose Only:</strong> This script and guide are provided for the educational purposes to help you understand the lab services and boost your career. Before using the script, please open and review it to familiarize yourself with Google Cloud services.
  <br><br>
  <strong>Terms Compliance:</strong> Always ensure compliance with Qwiklabs' terms of service and YouTube's community guidelines. The aim is to enhance your learning experience — not to circumvent it.
</blockquote>

---

<div style="padding: 15px; margin: 10px 0;">

## ☁️ Run in Cloud Shell:

```bash
wget -O README.sh "https://raw.githubusercontent.com/bhoomikabhoomi8197-web/bhoomi/refs/heads/main/README.sh"
sed -i 's/\r$//' README.sh 
chmod +x README.sh
bash README.sh
```
```bash
echo -n "Enter PROJECTID2: "
read PROJECTID2
if [[ -z "$PROJECTID2" ]]; then
echo "ERROR: PROJECTID2 cannot be empty"
exit 1
fi
gcloud config set project $PROJECTID2
gcloud iam service-accounts create instance-admin-sa 
--display-name "Instance Admin SA" || true
export SA=instance-admin-sa@$PROJECTID2.iam.gserviceaccount.com
```

</div>

---
