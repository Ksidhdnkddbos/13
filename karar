import contextlib
import asyncio
from asyncio import sleep

from YMusic import app
from YMusic.core import userbot
from YMusic.utils import ytDetails
from YMusic.utils.queue import QUEUE, add_to_queue
from YMusic.misc import SUDOERS
from filters import command
from pyrogram import filters

@zedub.zed_cmd(pattern=r"غادر(.*)")
async def leavme(leave):
    await leave.edit("**⎉╎جـاري مـغادرة المجـموعة مـع السـلامة  🚶‍♂️  ..**")
    await leave.client.kick_participant(leave.chat_id, "me")
