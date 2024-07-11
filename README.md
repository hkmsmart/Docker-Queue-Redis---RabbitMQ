# Docker Queue Redis - RabbitMQ
 
Docker üzerine redis ve rabbitmq kurarak portlarını ve volumeslarını ayarlayarak çalıştıracağız.
projeyi github üzerinden indirip aşağıdaki kodu yazarak çalıştırabilirsiniz.

github

>    docker-compose up -d


docker-compose.yaml dosya içeriği:

version  - Bu, Docker Compose dosya biçiminin sürümüdür. 3.7 sürümünü kullanıyoruz.

services  - Bu, kapsayıcıların listesini ve ayarlarını tanımladığımız bölümdür. Bizim durumumuzda, bir hizmet tanımlıyoruz 

redis  - Bu, hizmetimizin adıdır.

rabbitmq  - Bu, hizmetimizin adıdır.

image  - Bu, kapsayıcımızı oluşturmak için kullanacağımız Redis ve Rabbitmq görüntüsünün adıdır.

restart  - Bu, Docker'a, durması veya arızalanması durumunda servis kapsayıcısını yeniden başlatmasını söyleyen bir ayardır.

ports  - Bu, kapsayıcının hangi bağlantı noktalarının ana sistemde erişilebilir olması gerektiğini tanımlayan bir ayardır. 

volumes  - Bu, ana sistemdeki hangi dizinlerin kapsayıcı içinde erişilebilir olması gerektiğini tanımlayan bir ayardır. 

environment  - Bu kapsayıcısı için ortam değişkenlerini tanımlamamızı sağlayan bir ayardır. 

blogger link: https://hkmsmart.blogspot.com/2024/07/docker-redis-ve-rabbitmq.html
