# base Ansible Runner image
FROM quay.io/colin_mccarthy/ansible-runner:stable_1.4.x



# dependencies 
RUN pip3 install --no-cache-dir pysnow==0.7.16 



# required
CMD ["ansible-runner", "run", "/runner"]




