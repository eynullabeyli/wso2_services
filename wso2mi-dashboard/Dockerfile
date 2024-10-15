FROM wso2/wso2mi-dashboard:latest

WORKDIR /home/wso2carbon

COPY ./conf/deployment.toml /home/wso2carbon/wso2mi-dashboard-4.1.0/conf/deployment.toml

EXPOSE 9445

CMD ["/home/wso2carbon/wso2mi-dashboard-4.1.0/bin/dashboard.sh"]
