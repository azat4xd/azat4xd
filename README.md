### Hi there 👋

<!--
**azat4xd/azat4xd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
---
hızlı başlangıç kodu 5 dk giriş
<!---
nurasli6677/nurasli6677 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<? xml sürümü = " 1.0 " kodlama = " utf-8 " ?>
< kök >
	< resheader  name = " resmimetype " >
		< değer >metin/microsoft-resx</ değeri >
	</ yeniden başlık >
	< yeniden başlık  adı = " sürüm " >
		< değer >2.0</ değer >
	</ yeniden başlık >
	< yeniden başlık  adı = " okuyucu " >
		< değer >System.Resources.ResXResourceReader, System.Windows.Forms, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</ değeri >
	</ yeniden başlık >
	< yeniden başlık  adı = " yazar " >
		< değer >System.Resources.ResXResourceWriter, System.Windows.Forms, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</ değer >
	</ yeniden başlık >
	< veri  adı = " SkipText "  xml : boşluk = " koru " >
    < değer >ATLA</ değeri >
  </ veri >
  < veri  adı = " TryDemoText "  xml : boşluk = " koru " >
    < değer >DEMO'YU DENE</ değeri >
  </veri >
  < veri  adı = " ChartPage_Title "  xml : boşluk = " koru " >
    < değer >Depolarınız hakkında genel bilgi alın</ value >
  </veri >
  < veri  adı = " ChartPage_Body_ShowAllTraffic "  xml : boşluk = " koru " >
    < value >Grafikler, deponuzla ilgili tüm zaman gösterir:</ value >
  </ veri >
  < veri  adı = " ChartPage_Body_ZoomInOut "  xml : boşluk = " koru " >
    < değer >Bililmek üzere kesin bir şekilde için yakınlaştırın/uzaklaştırın</ değeri >
  </ veri >
  < veri  adı = " ChartPage_Body_LongPress "  xml : boşluk = " koru " >
    < value >Keşin Sayıların Resimleri See için grafiğe uzun basın</ value >
  </veri >
  < veri  adı = " ConnectToGitHubPage_Title "  xml : boşluk = " koru " >
    < value >Github'a bağlan</ value >
  </ veri >
  < veri  adı = " ConnectToGitHubPage_Body_GetStarted "  xml : boşluk = " koru " >
    < value >GitHub > bağlayarak çalışarak veya GitTrends'i gezmek için demo çalışma!< / value
  </ veri >
  < veri  adı = " GitTrendsPage_Title "  xml : boşluk = " koru " >
    < value >GitTrends'e Hoşgeldiniz</ value >
  </ veri >
  < veri  adı = " GitTrendsPage_Body_GitTrendsHelps "  xml : boşluk = " koru " >
    < value >GitTrends, GitHub depolarınızı izlemenize yardımcı olur:</ value >
  </veri >
  < veri  adı = " GitTrendsPage_Body_MonitorGitHubRepos "  xml : boşluk = " koru " >
    < value >GitHub Repo Görüntülemeleri, Klonları, Kolları, Yıldızları ve Konuları İzleyin</ value >
  </veri >
  < data  name = " GitTrendsPage_Body_DiscoverReferringSites "  xml : space = " koru " >
    < value >Atıfta Bulunan Siteleri Keşfedin</ value >
  </ veri >
  < veri  adı = " NotificationsPage_Title "  xml : boşluk = " koru " >
    < value >Depolar populer olunca beylik olun</ value >
  </ veri >
  < data  name = " NotificationsPage_Body_MoreTrafficThanUsual "  xml : boşluk = " koru " >
    < value >GitTrends, GitHub depolarınız normalden daha fazla trafikte sizi bilgilendirecektir.</ value >
  </veri >
  < veri  adı = " EnableNotifications "  xml : boşluk = " koru " >
    < value >Bildirimleri Etkinleştir</ value >
  </veri >
</ kök >
name: Deployment
on: [push]
jobs:
  deploy:
    name: Deploy
    runs-on: ubuntu-latest
    steps:
      ...
      - name: Set up tools
        uses: daisaru11/setup-cd-tools@v1
        with:
          kubectl: '1.6.0'
          kustomize: '3.5.4'
      ...
git clone https://github.com/sundowndev/PhoneInfoga
cd PhoneInfoga/
python3 -m pip install -r requirements.txt
