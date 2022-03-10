FROM Manuth/ManuthMax:public

RUN git clone https://https://github.com/ManuthTech /root/ManuthMax
WORKDIR /root/ManuthMax/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g

CMD ["node", "assets/module.js"]
