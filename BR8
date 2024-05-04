const express = require("express");
const app = express();

app.listen(() => console.log("Server started"));

app.use('/ping', (req, res) => {
  res.send(new Date());
});
//اكواد لا تحذفها
const Discord = require('discord.js');
require("events").EventEmitter.defaultMaxListeners = 9999999999999999999999999999;
const client = new Discord.Client();
const cmd = require("node-cmd");
const ms = require("ms");
const fs = require('fs');
const ytdl = require("ytdl-core");
const canvas = require("canvas");
const convert = require("hh-mm-ss")
const util = require("util")
const gif = require("gif-search");
const jimp = require("jimp");
const guild = require('guild');
const hastebins = require('hastebin-gen');
const getYoutubeID = require('get-youtube-id');
const pretty = require("pretty-ms");
const moment = require('moment');
const request = require('request');
const dateFormat = require('dateformat');
//صليت على سيدنا محمد اليوم😊؟
const prefix = "!"//⟸ بادئه البوت او برفكس
let havaline = 'https://media.discordapp.net/attachments/987329851864272926/987375415079366676/Picsart_22-06-17_18-16-24-882.png?width=1025&height=35';//⟸ رابط الخط 
//كود الحاله
client.on("ready", () => {
  console.log(`Prefix bot : ${prefix}`)
  console.log(`Bot is done = hava dev`)
  client.user.setActivity({ type: "PLAYING", name: `حاله البوتك` });//// كود الحاله
});

//الامر التفعيل
client.on('message', message => {
  if (message.content.startsWith(prefix + 'تفعيل')) { //تقدر تغير الامر
    let member = message.mentions.members.first();
    let user = message.mentions.members.first(); if (!message.member.roles.cache.has('1139788203310731264'))//ايدي الرتبه المسؤوله عن التفعيل
      if (!message.member.roles.cache.has('1139788203310731264'))//ايدي الرتبه المسؤوله عن التفعيل
        if (!message.member.roles.cache.has('1139788203310731264'))  //ايدي الرتبه المسؤوله عن التفعيل
          return message.reply(`**عفوا ي اخي انت لا تمتلك الصلاحيات الكافيه لقيام بالامر | :x: **`)
    if (!member) return message.reply('منشن العضو')
    //ايدي رتب البوت يعطيها للمفعل
    let role = message.guild.roles.cache.get('1139788366863421564');
    //ايدي الرتبه يلي ياخذها المفعل 
    let role2 = message.guild.roles.cache.get('1139788366863421564');//ايدي الرتبه يلي ياخذها المفعل
    let role3 = message.guild.roles.cache.get('1139788366863421564');//ايدي الرتبه يلي تنسحب من المفعل     
    //لا تعدل شي من تحت👇   
    member.roles.add(role);'1139788366863421564'
    member.roles.add(role2);'1139788366863421564'
    member.roles.remove(role3);'1139788369279332372'
    //اذا بدك تزيد رتب التفعيل ادخل سيرفري و تواصل معي 
    //https://discord.gg/7UQcSXRKxP

    //رساله التفعيل
    message.channel.send(new Discord.MessageEmbed()
      .setDescription(`** عـزيـزنـا الـمـواطـن : ${user}
تـم تفعـيلك فـي سيرفر  
نـرجـو منك الإلـتزام بالقـوانـين والأنظمة داخل الـسيرفر **`)//تقدر تعدلها
      .setImage(`${havaline}`)
      .setColor('RANDOM')
    )
    //رساله يلي تيجي المفعل بالخاص  
    const embed1 = new Discord.MessageEmbed()
      .setColor('RANDOM')
      .setDescription(`
تـم تفعـيلك فـي سيرفر  
نـرجـو منك الإلـتزام بالقـوانـين والأنظمة داخل سيرفر 𝐋𝐌  `)//تقدر تغير الرساله
      .setImage(`${havaline}`)
    user.send(embed1)

  }
});


//كود التوكن
client.login(process.env.token);
//ليش تستخدم البروجكت و انت مو مشترك بالقناه😤
