Tạo public_key và private_key để ssh đến máy chủ. Mở Terminal trên máy tính của bạn và thực hiện lệnh sau

'''
ssh-keygen -t rsa -C $(hostname) -f "$HOME/.ssh/id_rsa" -P "" ; cat ~/.ssh/id_rsa.pub
'''

