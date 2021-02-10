# discord-bot
import discord
import json
bot = discord.Client()

@bot.event()
async def on_message(message):
   if message.content = '!hello':             #you can also specify where do you want to send the message by doing- channel = bot.get_channel(<channel_id>)
   await message.channel.send('Hi!')         
