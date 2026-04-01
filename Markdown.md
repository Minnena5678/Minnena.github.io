# Password เครื่อง 1606

- Email : junior.sw.nextschool@gmail.com
- PassWord : Aq1sw2de3fr4

## Tree , GitHub

- Email : junior.sw.nextschool@gmail.com
- PassWord : Aq1sw2de3fr4

## Passphrase ของ ssh key

- ไม่มีกด Enter ได้เลย

# Project Vaccine

- ~/Sites/SoftwareDevelper/Denso-learning/backend/views/vaccine
- ~/Sites/SoftwareDevelper/Denso-learning/backend/views/vaccine-student

# Project Venue

- ~/Sites/SoftwareDevelper/Denso-learning/backend/views/venue
- ~/Sites/SoftwareDevelper/Denso-learning/backend/views/venue-booking

# Project PDF

- อยู่ตามโฟสเดอร์ในหน้า Desktop

  - ข้อมูลรายละเอียดของนักเรียนโรงเรียนบ้านบึง
    - ~/Desktop/infoรายละเอียดบุคคล
  - สรุปแบบประเมินพฤติกรรมของนักเรียนตามค่านิยมหลักคนไทย 12 ประการ
    - ~/Desktop/ค่านิยมหลัก 12
  - ตารางเรียน
    - ~/Desktop/ตารางเรียน
  - บัตรผู้สมัครโรงเรียนบ้านบึง
    - ~/Desktop/บัตรผู้สมัคร
  - ใบมอบตัวโรงเรียนบ้านบึง
    - ~/Desktop/ใบมอบตัว
  - ใบสมัครเรียนโรงเรียนบ้านบึง
    - ~/Desktop/ใบสมัครเข้าศึกษา
  - แบบบันทึกผลการประเมินกิจกรรมพัฒนาผู้เรียน
    - ~/Desktop/แบบบันทึกผลการประเมิน
  - แบบประเมินภาวะซึมเศร้าในวัยรุ่น
    - ~/Desktop/แบบประเมินซึมเศร้า
  - ปพ.6
    - ~/Desktop/ปพ6
    - รวมเป็นไฟล์เดียว
      - ~/Desktop/ปพ6/รวม
  - ปพ.9
    - ~/Desktop/ปพ9
  - รายงานผลการเรียนโรงเรียนประถม
    - ~/Desktop/รายงานผลการเรียนประถม
  - รายงานผลการเรียนโรงเรียนอนุบาล
    - ~/Desktop/รายงานผลการเรียนอนุบาล

- มีอยู่ใน ~/Sites/SoftwareDevelper/Denso-learning/backend/views/pdf
  - ใบสมัครเข้าศึกษาของโรงเรียนบ้านบึง = study.php
  - บัตรผู้สมัครของโรงเรียนบ้านบึง = studycard.php
  - ใบมอบตัวนักเรียนของโรงเรียนบ้านบึง = studyfrom.php

# Project Widgets

- ช่วงวันที่
  - DateRange.php
  - ~/Sites/SoftwareDevelper/Denso-learning/common/widgets/DateRange.php
- Filter รายละเอียดข้อมูลของนักเรียน
  - FilterWidget.php
  - ~/Sites/SoftwareDevelper/Denso-learning/common/widgets/FilterWidget.php
- เลือกว่าจะใช้ Text,Select,Select2,Dropdown
  - SelectText.php
  - ~/Sites/SoftwareDevelper/Denso-learning/common/widgets/SelectText.php

# Python ข้อมูลเด็กจาก โรงเรียนบ้านบึง

- Code
- วิธีใช้งาน
  - cd ~/Sites/SoftwareDevelper/Example/Selenium/finish เข้าโฟสเดอร์
  - python3 banbung_student_list.py ทำการรัน python
- banbung_student_list.py
- ~/Sites/SoftwareDevelper/Example/Selenium/finish/banbung_student_list.py

- JS
  - students_all. js
  - ~/Sites/SoftwareDevelper/Example/Selenium/finish/students_all.js

# Mac System

- ระบบ MacOS
- Homebrew

  - เปิด Terminal
  - วาง " /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" "

- itern2
  - วางไว้ใน Terminal brew install --cask iterm2
  - ติดตั้ง Oh-my-Zsh " sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "
  - ติดตั้ง powerlevel10k " brew install powerlevel10k "
  - เปิด (code ~/.zshrc) หรือ ใช้ nano หรือ อะไรก็ได้ตามที่ถนัด แล้วนำ ZSH_THEME="powerlevel10k/powerlevel10k" ใส่
  - ทำการใช้คำสั่ง source ~/.zshrc

# Git

- Git

  - ติดตั้ง brew install git

    - วิธีใช้งาน
      - git clone https://github.com/user/repo.git โคลน git ที่เลือก
      - git status ตรวจสอบสถานะของงานว่าไฟล์ไหนโดน แก้ เพิ่ม ลบ
      - git add .
      - git commit -m "ข้อมูลที่แก้ไข" Commit การเปลี่ยนแปลง
      - git branch ดู branch ที่มีอยู่
      - git branch ชื่อฟังก์ชัน สร้าง branch ขึ้นมาใหม่
      - git checkout ชื่อฟังก์ชัน ย้าย branch
      - git pull origin main อัพเดตงานจาก git ลงโปรเจค
      - git push origin develop Pushงานขึ้น git

- Git Flow

  - Git Command
  - ติดตั้ง brew install git-flow-avh

    - วิธีใช้งาน
      - git flow init เมื่อเข้าไปในโปรเจคครั้งแรก
      - git flow feature start ชื่อฟังก์ชัน เริ่มฟังก์ชั่น
      - git flow feature finish ชื่อฟังก์ชัน จบฟังก์ชั่น

# Docusaurus

- วิธีการใช้งาน

  - Run  
    "npx create-docusaurus@latest name_project classic"
  - cd name_project
  - npm install / yarn install

  - npm run build
  - npm run start(รันเซิฟเวอร์)

# Dioxus

- Expo go

  - สแกน QR code เพื่อใช้งานบนมือถือได้

  - ติดตั้ง npm install -g expo-cli
  - expo init ตามด้วยชื่อโปรเจค
  - cd ชื่อโปรเจค
  - expo start

- React , React Native
- Node lib
- Rust

# การเขียน Md , tree

- วิธีการเขียน

- done -เสร็จ
- doing -กำลังทำอยู่
- todo -คิดไว้ว่าจะทำ
- prom -ปัญหา
- learn -เรียนอะไรไปบ้าง

# Cyber Security

- วิธีป้องกันข้อมูลในรูปแบบต่างๆ
- ประเภทของการโจรกรรมข้อมูล
- Web Scapping
- SQL Injection

# tmux

- ติดตั้ง gh ghq ก่อน

  - brew install gh ติดตั้ง
  - brew install ghq ติดตั้ง

  - gh auth login
  - gh auth status

  - mkdir -p ~/sandbox/scripts สร้างโฟสเดอร์
  - touch ~/sandbox/scripts/gq.sh สร้างไฟล์และนำ https://gist.github.com/pangpond/e65ddd8abc7bc5c11b0babf98dc2cb57 code ในนี้ไปแปะ

  - nano ~/.zshrc (หรือ code ก็ได้) เพิ่ม source ~/sandbox/scripts/gq.sh ลงไปข้างล่างสุด บันทึก
  - source ~/.zshrc

- วิธีการทำงาน

  - brew install tmux
  - " tmux " = เปิด session ใหม่
  - tmux ls = ดูว่า tmux มี session อะไรบ้าง
  - tmux a -t ตามด้วย session = เพื่อเชื่อมต่อ

  - command in tmux

    - ต้องกด Ctrl + b ก่อนการทำทุกอย่าง
    - Ctrl + b % = แบ่ง panel แนวตั้ง
    - Ctrl + b '(ง) = แบ่ง panel แนวนอน
    - Ctrl + b d = ปิด session แต่ยังทำงานอยู่
    - tmux kill-session -t ตามด้วย session = เพื่อลบ session
    - tmux kill-server = ลบทุก session ที่สร้าง

# mPDF / PHP

- วิธีทำ PDF ของ php
- การจัดเอกสาร PDF
- วิธีจัด HTML ให้ดูไม่รกตา

# Yii2

- Gii
  - ชื่อเว็บไซต์/index.php?r=gii
- วิธีติดตั้ง

  - brew install composer
  - composer create-project --prefer-dist yiisoft/yii2-app-advanced ชื่อโปรเจค ทำการสร้างโปรเจคแบบ Adv (มีแบบ Basic ด้วย)
  - cd myapp เข้าไปที่โปรเจค
  - php init เริ่มโปรเจค

- Mirgrate

  - php yii migrate รัน Migrate
  - php yii migrate/create ชื่อMigrate ทำการสร้าง migrate
  - php yii migrate up / down อัพ migrate หรือ นำ migrate ล่าสุดออก

- Nginx

  - brew install nginx ติดตั้ง Nginx
  - brew install mkcert ทำการติดตั้ง
  - brew install nss ทำการติดตั้ง

  - mkcert -install ทำครั้งแรกครั้งเดียว
  - mkcert WebSiteName.local
  - เพิ่ม ssl_certificate , ssl_certificate_key ใน servers.conf

- openSSL

  - brew install nginx ติดตั้ง
  - code /etc/hosts เพิ่มชื่อเว็บไซต์
  - openssl req -x509 -newkey rsa:2048 -keyout WebSiteName.key -out WebSiteName.crt -sha256 -days 999 -nodes \
    -subj "/CN=WebSiteName" ทำการสร้างใบ certs
  - เพิ่ม ssl_certificate , ssl_certificate_key ใน servers.conf

- คำสั่ง Nginx

  - brew services start nginx เริ่ม
  - brew services stop nginx หยุด
  - brew services restart nginx รีสตาร์ส

- SSH KEY

  - ls -al ~/.ssh ตรวจสอบว่ามี id_rsa หรือ id_ed25519 ไหม
  - ssh-keygen -t ed25519 -C "อีเมล Github" สร้าง key
  - cat ~/.ssh/id_ed25519.pub คัดลอกKey
  - ไป GitHub → Settings → SSH and GPG keys → New SSH key
  - ตั้งชื่อ key
  - วาง public key ลงในช่อง Key
  - กด Add SSH key

# Data

- Database
- Query
- การ Query ข้อมูลให้มีความง่ายต่อการนำไปใช้งาน และมีประสิทธิภาพ

# ทั่วไป

- การนำเสนอ
- แนวทางการขาย
- วิธีการเตรียมข้อมูลเพื่อไปนำเสนอ
- การรับมือลูกค้า
- การออกแบบระบบ
- การสรุปข้อมูลให้เข้าใจ
- การคุยกับ Ai ยังไงให้มีประสิทธิภาพ
- มุมมองการใช้ชีวิต
