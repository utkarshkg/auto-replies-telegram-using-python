# auto-replies-telegram-using-python

from __future__ import unicode_literals
from telethon import TelegramClient, events, sync

# These example values won't work. You must get your own api_id and
# api_hash from https://my.telegram.org, under API Development.

api_id = #write yours
api_hash = #'write from telegram api website'

client = TelegramClient('session_name', api_id, api_hash)
client.start()

import time
from telethon import utils
from telethon.tl.functions.messages import SendMessageRequest
import telepot
from telepot.namedtuple import ReplyKeyboardMarkup, KeyboardButton
from emoji import emojize
client.send_message('@JuraWorldBot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@JuraWorldBot', '\U0001F381'' Bonus', link_preview=False)
time.sleep(120)

client.send_message('@CarBTC_bot', '\start', link_preview=False)

client.send_message('@CarBTC_bot', '\U0001F381'' Bonus', link_preview=False)
time.sleep(60)

client.send_message('@animalfarm_V2_Bot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@animalfarm_V2_Bot', '\U0001F381'' Bonus' , link_preview=False)
time.sleep(120)

client.send_message('@DinoParkBot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@DinoParkBot', '\U0001F381'' Bonus!!!', link_preview=False)
time.sleep(120)

client.send_message('@Cashzoobot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@Cashzoobot', '\U0001F381'' Bonus', link_preview=False)
time.sleep(120)

client.send_message('@mfarm_bot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@mfarm_bot', '\U0001F36C'' Bonus', link_preview=False)
time.sleep(120)

client.send_message('@claim_bitcoin_with_me_v1_bot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@claim_bitcoin_with_me_v1_bot', '\U0001F381'' Bonus', link_preview=False)
time.sleep(120)

client.send_message('@eCryptoMiningBot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@eCryptoMiningBot', '\U0001F49A'' Daily Bonus', link_preview=False)
time.sleep(120)

client.send_message('@HouseMoneyBot', '\start', link_preview=False)
time.sleep(60)
client.send_message('@HouseMoneyBot', '\U0001F381'' Bonus' , link_preview=False)
time.sleep(120) 
client.send_message('@eubtcbot', '\U0001F3B0'' BONUS' , link_preview=False)

