FROM wso2/wso2am:latest

#COPY ./repository/deployment.toml /home/wso2carbon/repository/conf/deployment.toml

COPY ./repository/deployment.toml /home/wso2carbon/wso2am-4.3.0/repository/conf/deployment.toml

EXPOSE 9443 9766 8281 8243

CMD ["/home/wso2carbon/bin/wso2server.sh"]
