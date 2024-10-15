FROM wso2/wso2is:latest

WORKDIR /home/wso2carbon

COPY ./repository/deployment.toml /home/wso2carbon/wso2is-7.0.0/repository/conf/deployment.toml

EXPOSE 9444 9764

CMD ["/home/wso2carbon/bin/wso2server.sh"]
