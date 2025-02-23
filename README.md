# elk
1  sudo apt update -y
    2  curl -fsSL https://artifacts.elastic.co/GPG-KEY-elasticsearch |sudo gpg --dearmor -o /usr/share/keyrings/elastic.gpg
    3  echo "deb [signed-by=/usr/share/keyrings/elastic.gpg] https://artifacts.elastic.co/packages/7.x/apt stable main" | sudo tee -a /etc/apt/sources.list.d/elastic-7.x.list
    4  sudo apt update
    5  sudo apt install elasticsearch
    6  curl localhost:9200
    7  sudo systemctl enable elasticsearch
    8  sudo systemctl start elasticsearch
    9  curl localhost:9200
   10  sudo apt install kibana
   11  sudo systemclt enable kibana
   12  sudo systemctl enable kibana
   13  sudo systemctl start kibana
   14  curl -I localhost:5601
   15  sudo apt install nginx -y
   16  ss -nltld
   17  ss -ntulp
   18  sudo systemctl status nginx
   19  sudo /etc/nginx/sites-enabled
   20  cd /etc/nginx/sites-enabled
   21  ls
   22  echo "" |
   23  echo "" | sudo tee default
   24  cat default
   25  sudo vim default
   26  cat default
   27  sudo systemctl restart nginx
   28  sudo systemctl restart nginx kibana
   29  echo "kibanaadmin:`openssl passwd -apr1`" | sudo tee -a /etc/nginx/htpasswd.users
   30  cd /etc/nginx/sites-enabled
   31  ls
   32  sudo vim default
   33  cat default
   34  sudo systemctl restart nginx
   35  sudo apt install metricbeat
   36  sudo vim /etc/metricbeat/metricbet.yaml
   37  sudo vim /etc/metricbeat/metricbeat.yaml
   38  sudo vim /etc/metricbeat/metricbeat.yml
   39  sudo metricbeat modules list
   40  sudo metricbeat modules enables nginx
   41  sudo metricbeat modules list
   42  sudo metricbeat
   43  sudo metricbeat modules list
   44  sudo metricbeat modules enables nginx
   45  sudo metricbeat modules enable nginx
   46  sudo metricbeat modules list
   47  sudo systemctl start meticbeat
   48  sudo systemctl start metricbeat
   49  sudo systemctl enable metricbeat
   50  sudo metricbeat setup
   51  sudo apt install filebeat -y
   52  sudo vim /etc/filebeat/filebeat.yml
   53  sudo filebeat module list
   54  sudo filebeat modules list
   55  sudo filebeat modules enable nginx
   56  sudo filebeat modules list
   57  sudo systemctl start filebeat
   58  sudo systemctl enable filebeat
   59  sudo filebeat setup
   60  history
