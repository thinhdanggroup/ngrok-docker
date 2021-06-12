FROM corbinu/ssh-server

WORKDIR /app

COPY . .

RUN cat public_key | cat >> /root/.ssh/authorized_keys

EXPOSE 22

ENTRYPOINT ["ssh-start"]
CMD ["ssh-server"]