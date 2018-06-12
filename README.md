# GIF_generator_playbooks
Repository contain playbooks to set GIF_generator aplication instances.

Before use, create file named servers.ini containing:
```
[web_nodes]
__YOUR_INSTANCE_IP__ ansible_user=ec2-user
```

To run GIF_generator_uploading playbook type in console:
`ansible-playbook -i serwers.ini install_animations_creator_page.yml --extra-vars "git_username=__YOUR_GIT_USERNAME__ git_email=__YOUR_GIT_EMAIL__"`
