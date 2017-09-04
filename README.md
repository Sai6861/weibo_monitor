# weibo_monitor
# main
from get_wb_id import get_wb_id
from get_updated_info import get_updated
from mail import mail


if __name__ == '__main__':
    get_wb_id()
    get_updated()
    mail()
