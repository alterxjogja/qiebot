

    // BOT VARIABLE // MULTIPLE WITH ',' TANPA SPASI 
    TZ: 'Asia/Jakarta',
    URL_RULES: 'https://alterxjogja.github.io',

    TRIGGER: 'fuck,ngentod,halo,hey',
    ADMIN: '1131977140633710593, 1119544717555822592',
    MODERATOR: '982278529',

    DB_SEND_SIZE: 5000,

    TOKEN_RESET_DAY: 1, //https://en.wikipedia.org/wiki/ISO_week_date
    TOKEN_NAME: 'Ticket',

    BOT_STATUS: true,
    BOT_STATUS_RESPONSE: 'Maaf BOT sedang OFF. Tunggu pengumuman dari Admin.',

    REPLY_TIGGER_UNKNOWN: true,
    REPLY_TIGGER_UNKNOWN_RESPONSE: 'Trigger tidak ditemukan, silahkan kirim /menu atau baca PERATURAN BASE ${URL_RULES} dahulu!',

    GREET_NEW_FOLLOWER: true,
    GREET_NEW_FOLLOWER_RESPONSE: 'Terima kasih udah follow Base, silahkan kirim /menu atau baca PERATURAN BASE ${URL_RULES} dahulu!',

    GREET_NEW_FOLLOWING: true,
    GREET_NEW_FOLLOWER_RESPONSE: 'Yey Kamu difollow Base ini, silahkan kirim /menu atau baca PERATURAN BASE ${URL_RULES} dahulu!',
    //TOKEN RATE 

    RATE_REPLY: 2500,
    RATE_REPLY_MIN: 0.2,
    RATE_REPLY_MAX: 0.9,
    RATE_RETWEET: 1000,
    RATE_RETWEET_MIN: 0.2,
    RATE_RETWEET_MAX: 0.9,
    RATE_LIKE: 3000,
    RATE_LIKE_MIN: 0.1,
    RATE_LIKE_MAX: 0.4,
    RATE_FOLLOWING_ADDITIONAL: 0.3,
    RATE_RETWEET_PINED: 1,

    TOKEN_STATUSES: 2500,
    TOKEN_STATUSES_MAX: 4,
    TOKEN_FOLLOWER: 1000,
    TOKEN_FOLLOWER_MAX: 4,
    TOKEN_ACCOUNT_AGE: 0.1,
    TOKEN_ACCOUNT_AGE_MAX: 0.3,
    TOKEN_FOLLOWING: 5,
    TOKEN_USER_ACTIVITY: 0.02,
    TOKEN_USER_ACTIVITY_MAX: 5,
    TOKEN_MINIMUM_DEFAULT: 3,
    TOKEN_MAXIMUM_DEFAULT: 25,

    TOKEN_DEFAULT_ADMIN: 100,
    TOKEN_DEFAULT_MODERATOR: 55,

    TOKEN_FARM_TIME: 1, //minutes minimal & maximal  1.99 x TOKEN_FARM_TIME


    //FILTER WORDS

    BLACKLIST_WORDS: 'cc,open,bo,b0,angle,angl3',
    BLACKLIST_WORDS_RESPONSE: 'Terdapat blacklist word di Menfess Kamu, ketik /blacklist untuk melihat daftar blacklist. Terdeteksi :',

    SIMILARITY_CHECK_TWEETS: 10, //number of last tweet to be checked
    SIMILARITY_THRESHOLD: 0.9,
    SIMILARITY_RESPONSE: 'Menfess serupa sudah diposting sebelumnya. Untuk menghindari suspend dari Twitter karena spam Menfess kamu tidak bisa dikirimkan',

    INTERVAL_PER_MENFESS: 1, //menit
    INTERVAL_PER_MENFESS_RESPONSE: 'Mengirim Menfess dibatasi setiap ${INTERVAL_PER_MENFESS} menit.',

    // MENFESS SETTING VARIABLE

    
    MIN_MENFESS_LENGTH_CHARACTER: 10,
    MAX_MENFESS_LENGTH_CHARACTER: 1120,
    MENFESS_LENGTH_CHARACTER_RESPONSE: 'Minimal jumlah karater Menfess adalah ${MIN_MENFESS_LENGTH_CHARACTER} dan Maksimal ${MAX_MENFESS_LENGTH_CHARACTER}.',

    ALLOW_MENTION: false,
    ALLOW_MENTION_RESPONSE: 'Tidak boleh mention User lain.',
    ALLOW_URL_FROM_ANOTHER_USER: false,
    ALLOW_URL_FROM_ANOTHER_USER_RESPONSE: 'Tidak boleh mengirim link dari Akun lain.',
    ALLOW_URL_FROM_OUTSIDE_TWITTER: false,
    ALLOW_URL_FROM_OUTSIDE_TWITTER_RESPONSE: 'Tidak boleh mengirim link dari luar Twitter',

    TEXT_BEFORE_MENFES: 'Sudah baca PERATURAN BASE ${URL_RULES} kan?. Kamu yakin mengirim Menfess ini?',

    OPT_BEFORE_MENFES_Y: 'Ya',
    OPT_BEFORE_MENFES_Y_D: 'Fuck me please',
    OPT_BEFORE_MENFES_Y_ID: 'opt_1',
    OPT_BEFORE_MENFES_N: 'Tidak',
    OPT_BEFORE_MENFES_N_D: 'Yes harder babe',
    OPT_BEFORE_MENFES_N_ID: 'opt_2',

    TEXT_QUEUE_MENFES: 'Silahkan tunggu Menfess Kamu sedang antri untuk diposting. Kirim /cancel untuk membatalkan. Antrian Menfess :',
    TEXT_AFTER_MENFES: 'Menfess Kamu telah diposting. Kirim /unsend untuk menghapus Menfess sebelum ${UNSEND_MAX_TIME} menit. Kirim /status untuk mengetahui ${TOKEN_NAME} Menfess kamu',
    TEXT_CANCEL_MENFES: 'Menfess Kamu sudah dibatalkan 👌',
    TEXT_CANCEL_NOT_FOUND_MENFES: 'Tidak ada Menfess yang bisa batalkan',

    TEXT_UNSEND_MENFES: 'Menfess Kamu sudah dihapus 👌',
    TEXT_UNSEND_TIMEOVER_MENFES: 'Maaf Menfess kamu sudah lebih dari batas ${UNSEND_MAX_TIME} menit, tidak bisa dihapus 👍',
    TEXT_UNSEND_NOT_FOUND_MENFES: 'Tidak ada Menfess yang bisa dihapus',
    GREETING_FOLLOWER: true,
    TEXT_FOLLOWED_RESPONSE: 'Terima kasih sudah follow base, silahkan kirim /menu dan baca PERATURAN BASE ${URL_RULES}.',

    TEXT_WARN_FOOTER: 'Silahkan baca PERATURAN BASE ${URL_RULES}.',

    UNSEND_MAX_TIME: 15, //mins


    // FILTER EGIBLE SENDER

    EGIBLE_ONLY_FOLLOWING: false,
    EGIBLE_FOLLOWING_MIN_FOLLOWER: 5,
    EGIBLE_NOT_FOLLOWING_MIN_FOLLOWER: 21,
    EGIBLE_FOLLOWING_MIN_ACCOUNT_AGE: 8, //day
    EGIBLE_NOT_FOLLOWING_MIN_ACCOUNT_AGE: 30, //day
    EGIBLE_NEW_FOLLOWER_WAITING_TIME: 72, //hours
    EGIBLE_FOLLOWING_STATUS_COUNT: 10,
    EGIBLE_NOT_FOLLOWING_STATUS_COUNT: 50,

    TEXT_DENY_MENFESS_HEADER: 'Kamu tidak diperbolehkan mengirim Menfess.',
    TEXT_DENY_ONLY_FOLLOWING: 'Hanya akun yang difollow base boleh mengirim Menfess.',
    TEXT_DENY_FOLLOWING_MENFESS_MIN_FOLLOWER: 'Minimal follower akun Kamu harus ${EGIBLE_FOLLOWING_MIN_FOLLOWER} jika difolback Base.',
    TEXT_DENY_NOT_FOLLOWING_MENFESS_MIN_FOLLOWER: 'Minimal follower akun Kamu harus ${EGIBLE_NOT_FOLLOWING_MIN_FOLLOWER}.',
    TEXT_DENY_FOLLOWING_MENFESS_MIN_ACCOUNT_AGE: 'Minimal umur akun Kamu harus ${EGIBLE_FOLLOWING_MIN_ACCOUNT_AGE} hari jika difolback Base.',
    TEXT_DENY_NOT_FOLLOWING_MENFESS_MIN_ACCOUNT_AGE: 'Minimal umur akun Kamu harus ${EGIBLE_NOT_FOLLOWING_MIN_ACCOUNT_AGE} hari.',
    TEXT_DENY_FOLLOWING_MENFESS_STATUS_COUNT: 'Minimal Tweet akun Kamu harus ${EGIBLE_FOLLOWING_STATUS_COUNT} jika difolback Base.',
    TEXT_DENY_NOT_FOLLOWING_MENFESS_MIN_STATUS_COUNT: 'Minimal Tweet akun Kamu harus ${EGIBLE_NOT_FOLLOWING_STATUS_COUNT}.',
    TEXT_DENY_NEW_FOLLOWER_WAITING_TIME: 'Follower baru base harus menunggu ${EGIBLE_NEW_FOLLOWER_WAITING_TIME} jam untuk bisa mengirim Menfess. Waktu tersisa:',
    TEXT_DENY_NOT_FOLLOWER: 'Hanya follower Base yang bisa mengirim Menfess.',
    TEXT_DENY_ZERO_TOKEN: '${TOKEN_NAME} Kamu untuk mengirim Menfess habis, kirim /status untuk mendapatkan ${TOKEN_NAME}.',
    TEXT_DENY_MENFESS_FOOTER: '${TEXT_COMMAND_RULE}.',


    // TEXT COMMAND
    TEXT_COMMAND_UNKNOWN: 'Command tidak diketahui.',
    TEXT_COMMAND_STATUS: 'Kirim /status untuk melihat status follower',
    TEXT_COMMAND_RULE: 'Ketik /rule untuk melihat aturan Menfess',
    TEXT_COMMAND_MENU: 'Ketik /menu untuk melihat menu follower.',

    // BANNED BOT
    BANNED_LVL_1: 3, //days
    BANNED_LVL_2: 7,
    BANNED_LVL_3: 14,
    BANNED_LVL_4: 30,
    BANNED_RESET_PERIOD: 90,//days
    TEXT_BANNED_HEADER: 'Kamu sedang di-banned oleh BOT  ',
    TEXT_BANNED_FOOTER: '. Banned kamu akan berakhir pada : ',


    MENU_STATUS: 'Status',
    MENU_STATUS_D: 'Status Akun',
    MENU_STATUS_ID: 'menu_1',

    MENU_RULE_BOT: 'Rule Bot',
    MENU_RULE_BOT_D: 'Peraturan Bot',
    MENU_RULE_BOT_ID: 'menu_2',

    MENU_RULE_MENFESS: 'Rule Menfess',
    MENU_RULE_MENFESS_D: 'Peraturan Menfess',
    MENU_RULE_MENFESS_ID: 'menu_3',

    MENU_RESET: 'Reset',
    MENU_RESET_D: 'Reset Bot jika error',
    MENU_RESET_ID: 'menu_10',
