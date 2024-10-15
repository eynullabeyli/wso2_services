FROM wso2/wso2mi:latest

WORKDIR /home/wso2carbon

#COPY ./repository/deployment.toml /home/wso2carbon/repository/conf/deployment.toml
COPY ./repository/deployment.toml /home/wso2carbon/wso2mi-4.3.0/conf/deployment.toml

EXPOSE 8290 8253 9201 9164

CMD ["/home/wso2carbon/wso2mi/bin/micro-integrator.sh"]