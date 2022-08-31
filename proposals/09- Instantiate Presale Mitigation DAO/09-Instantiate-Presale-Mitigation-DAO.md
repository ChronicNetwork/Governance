# Gov Prop 9: Instantiate Presale Mitigation DAO

## Details: This is a proposal to have the instantiation message of the CHT Presale Mitigation DAO signed & broadcasted by protocol itself.

### Details - Create Escrow Contract.

Chronic Network will continue to progress towards maximum decentralization by collaborating with the participants on a fair, transparent way to return presale tokens.

Below is the instantiation message that will be used to create the DAO: 

```json
{
    "admin": null,
    "automatically_add_cw20s": true,
    "automatically_add_cw721s": true,
    "description": "This is a DAO including all who have participated in the CHT presale process back in Q4 2021. ALL DAO MEMBERS VOTING POWER IS 1, & non transferrable. The Purpose of this DAO is to be able to acheive consensus on a fair way to mitigate the presale process that occured due to malpractice from previous core contributors.",
    "image_url": null,
    "name": "CHT Presale Mitigation DAO",
    "proposal_modules_instantiate_info": [
      {
        "admin": {
          "core_contract": {}
        },
        "code_id": 21,
        "label": "DAO_cht presale_cw-proposal-single",
        "msg": {
          "allow_revoting": false,
          "deposit_info": null,
          "max_voting_period": {
            "time": 259200
          },
          "only_members_execute": true,
          "threshold": {
            "threshold_quorum": {
              "quorum": {
                "percent": "0.50"
              },
              "threshold": {
                "percent": "0.499"
              }
            }
          }
        }
      }
    ],
    "voting_module_instantiate_info": {
      "admin": {
        "core_contract": {}
      },
      "code_id": 13,
      "label": "DAO_cht presale_cw4-voting",
      "msg": {
        "cw4_group_code_id": 15,
        "initial_members": [
          {
            "addr": "chronic16zmdz49qzqfwzc2nuh482jqvsm3um2qjtynazl",
            "weight": 1
          },
          {
            "addr": "chronic14eygcfdmwpl00nw2amqpujg73nyy59az6m6cez",
            "weight": 1
          },
          {
            "addr": "chronic1678zmd3hmjl8vatdqu9hesyx533sqpdr7a7xrg",
            "weight": 1
          },
          {
            "addr": "chronic1q8c84cpgcu0jzq2fj8d3e2566s2g9x5n29pu2s",
            "weight": 1
          },
          {
            "addr": "chronic1r3lwh5zzuwpwjqyz6hh9f4d7t9wlrlsgq3jz77 ",
            "weight": 1
          },
          {
            "addr": "chronic1vxmqnqmy9fjsdnjweuxq47vzz7juzdkd46dueq",
            "weight": 1
          },
          {
            "addr": "chronic14qf0sxuhzj2fdux9mpuh4um7xj869xqxuyns6e",
            "weight": 1
          },
          {
            "addr": "chronic16hmt5mz9dvtgtl7xds6p980n9zd56cdtfm4dsl",
            "weight": 1
          },
          {
            "addr": "chronic1ql2yp5j945r2uldna2kczpd4arqnxycruy33gr",
            "weight": 1
          },
          {
            "addr": "chronic1g24jgrwvqc6lhxj8ehesdkmwe3yva998ryqca7 ",
            "weight": 1
          },
          {
            "addr": "chronic19du42skszg5837qxa4pdmuzvhlpgc9x0rptclq",
            "weight": 1
          },
          {
            "addr": "chronic1t076ukjx9t5wm8w292a3qxfkk0pf75tyf2sjt8",
            "weight": 1
          },
          {
            "addr": "chronic1aad9mys0kg2qe7rrfe0zugkf0r9hdh2em59du3",
            "weight": 1
          },
          {
            "addr": "chronic1hjgjylx298juvne3hhdr0v07hh623d9mdtmjhw",
            "weight": 1
          },
          {
            "addr": "chronic14ua43vznemvgdw9rj477uacgedktrdvjemeurz",
            "weight": 1
          },
          {
            "addr": "chronic15m0fylnwxywsjanmj7nacm7ent2zplpyj0xqdt",
            "weight": 1
          },
          {
            "addr": "chronic15rhnhavt7q7c7es4fr284lvq6rnkg0njsgu936",
            "weight": 1
          },
          {
            "addr": "chronic1juaejwvhvmgnnsf6857kxykwz0rampex2yma86",
            "weight": 1
          },
          {
            "addr": "chronic17praexlxzyxsw4vp7ertwmunwa4rfa9vkerupu",
            "weight": 1
          },
          {
            "addr": "chronic1dttmz6hs86eahjvsyaynmv0ac850pmy778jv6j",
            "weight": 1
          },
          {
            "addr": "chronic1tz3r66u9chp8ha2sysfhrvf4rgx7wrql2yhz0a",
            "weight": 1
          },
          {
            "addr": "chronic12vj709mcrevdqznhk5va2679s0hfr8uqhdq0x3",
            "weight": 1
          },
          {
            "addr": "chronic1z5zq4gk2wzeamhqp0m5wumaftxl48vens3ehqs",
            "weight": 1
          },
          {
            "addr": "chronic1x0j6gvds5j479nm50530s5l0uvahas8fqlx6rj",
            "weight": 1
          },
          {
            "addr": "chronic184zvsass4hf6q6qsv8vx3hzyehtpsd8dp4e6au",
            "weight": 1
          },
          {
            "addr": "chronic1apc5upgffmdfd3jdd7mak4c8q40u8prxqfpych ",
            "weight": 1
          },
          {
            "addr": "chronic1yfzzmydlc4gyhswq4edzh59vlwmdkyx0rwjmjc",
            "weight": 1
          },
          {
            "addr": "chronic1na07txyfz07tf7ym7d8z2ulxrc3rwx2a8uaaxa",
            "weight": 1
          },
          {
            "addr": "chronic1337k25z25sxhdvcxuzq0unxe9990y9rm4czvkw",
            "weight": 1
          },
          {
            "addr": "chronic1upyk302zc0xc0sttjylkn9y7dr44xf4k3vxckh",
            "weight": 1
          },
          {
            "addr": "chronic1xw6sc0gacjrw5ua6lt2dmkmrsdng29r7hcym0a",
            "weight": 1
          },
          {
            "addr": "chronic1g5dryvfdmzm4363w2y0sq9jv6trp4nqtvk8fce",
            "weight": 1
          },
          {
            "addr": "chronic1e422r9zarpk3udvjzxr7aqpc8z4ur0hhzmyda5",
            "weight": 1
          },
          {
            "addr": "chronic1hc3gyett6famtgskxzu99fr7vcmfk79w8a9uvr ",
            "weight": 1
          },
          {
            "addr": "chronic14nnxm5aynhd3suf0vz0ak83nkfd6d3pthzqufd",
            "weight": 1
          },
          {
            "addr": "chronic1y2mzu78ldpz56a0w0fkr0pe8gur7qzpjpx2sv3",
            "weight": 1
          },
          {
            "addr": "chronic199sa2th3r20k2vvu3h6fgk4t77eqzlgtcnhv8p",
            "weight": 1
          },
          {
            "addr": "chronic1ajq0y2qzj5d7hrcu87y8g650ln9qjr6a735g04",
            "weight": 1
          },
          {
            "addr": "chronic1lrv08aqutdq56g7d6fp5jsrx7f5ah69gwjzjn6",
            "weight": 1
          },
          {
            "addr": "chronic1er9ljmgl2e7agfn6mh5w5lktap3mxjheqa3vp7",
            "weight": 1
          },
          {
            "addr": "chronic1lxg0shr539l5yg4z8gxzfu70mqdu077pljp9lm",
            "weight": 1
          },
          {
            "addr": "chronic168dn8zt9q04lav63cl5dh5vkhjdng83jqpucc5",
            "weight": 1
          },
          {
            "addr": "chronic1mjdeth9dlhpwhswkxdtxrqp2llsg4cw62xhs53",
            "weight": 1
          },
          {
            "addr": "chronic1v2chskwelx57khpddwgvjedal7rykvsuqzpgmp",
            "weight": 1
          },
          {
            "addr": "chronic1z7dt5c0mm29zvla7yqdacatvrkue20364nhkm0",
            "weight": 1
          },
          {
            "addr": "chronic1xhdu0c5jaa8cfltqp4n5766g8lc8azguqk6t3j",
            "weight": 1
          },
          {
            "addr": "chronic10c4ekgnuu8e27hvcltzuyfcaazvp7wexu8qdky",
            "weight": 1
          },
          {
            "addr": "chronic1v60t2x4utq8n6dgnw9p4c9d392tf7xffndqwrw",
            "weight": 1
          },
          {
            "addr": "chronic1pngnzu8wc2jymdaqfqwxkmu9f86axvpm00nwyg",
            "weight": 1
          },
          {
            "addr": "chronic1h9cursp2ft5fy0ddqrueqpx36l9h553p25wemp",
            "weight": 1
          },
          {
            "addr": "chronic1arrd795fj3ltqfjgehk7n8qygr796v3mjznqkn",
            "weight": 1
          },
          {
            "addr": "chronic1qzyn3tj799pzylf4uuagcpy3ts3h7xlfxzgknq",
            "weight": 1
          },
          {
            "addr": "chronic1uu832ww7p0sgtch5aqlxt6vhhznygcaqgyamu5",
            "weight": 1
          },
          {
            "addr": "chronic1sent6yyh3eg42g85wry0dc2egnsu9mvwl4sfwh",
            "weight": 1
          },
          {
            "addr": "chronic1zvtaz8l9xysxr6cpcuswvqclzyjarfq938wtnv",
            "weight": 1
          },
          {
            "addr": "chronic1ssuf8nqp0ktc45n2kwwf3xxdkyxqnhjqjmfpks",
            "weight": 1
          },
          {
            "addr": "chronic1mzndf9gu2kxygvr22mdnjy5fw2m8mwj82v7de6",
            "weight": 1
          },
          {
            "addr": "chronic13rwasdcjdgywac7xjkau7du05jsyuefe5266jy",
            "weight": 1
          },
          {
            "addr": "chronic146x8rd22hvy8qjtnu4zqp9kz4z9h9vk6j4xsxz",
            "weight": 1
          },
          {
            "addr": "chronic1er9ljmgl2e7agfn6mh5w5lktap3mxjheqa3vp6",
            "weight": 1
          },
          {
            "addr": "chronic147zm9s6zzcxw59xzc7jpympxn9d3rvtvrc4xmm",
            "weight": 1
          },
          {
            "addr": "chronic1nkqkkwl4fukacewfzshm0l0zmxj230z44maj3e",
            "weight": 1
          },
          {
            "addr": "chronic1d430sez5me2u2xecty0jewqhn8mvhj3y5dqk5n",
            "weight": 1
          },
          {
            "addr": "chronic18h2u7wy7z449pj3vlw3ln29ayplr6yuyk7ak62",
            "weight": 1
          },
          {
            "addr": "chronic19xyns090qvafqd0847krv89wr8zmv6q83a48wv",
            "weight": 1
          },
          {
            "addr": "chronic105uhqrfwxusscvtqndtflt49yevdt229p07ahl",
            "weight": 1
          },
          {
            "addr": "chronic15wvgq0gg9vz77ymz6lzr38707td39mgs57jp3c",
            "weight": 1
          },
          {
            "addr": "chronic1sent6yyh3eg42g85wry0dc2egnsu9mvwl4sfwh",
            "weight": 1
          },
          {
            "addr": "chronic1ltxc45vfyvvxr8j05z9he3u2jvrv4359mfuk3w",
            "weight": 1
          },
          {
            "addr": "chronic127jxnqsxxs0ljxnma3wk0unr876233pnaa6z8a ",
            "weight": 1
          },
          {
            "addr": "chronic16hzkhdypfayv40vhjj58z8v4mlyn5cawcrp6q4 ",
            "weight": 1
          },
          {
            "addr": "chronic1fczr673jqzaw3ha0t00wryeqeg7jzd6zt6qs99",
            "weight": 1
          },
          {
            "addr": "chronic13sf7yr28vmks3wklpw73q2dec5zwy4nynqcyah",
            "weight": 1
          },
          {
            "addr": "chronic1zqnq63xmsskhh2aqfh7jf3ge0c7fxuy0d830qw",
            "weight": 1
          },
          {
            "addr": "chronic10emhayxz9dmpa2cmcy7q4vcgrtz9rc0qz2svg4",
            "weight": 1
          },
          {
            "addr": "chronic1yyjqnxmmmzsuga6ehe30tf0m672yld6k2an9gd",
            "weight": 1
          },
          {
            "addr": "chronic1q6gewck6e0vq8xrz2jz4v9wk5yc8n92q597skf",
            "weight": 1
          },
          {
            "addr": "chronic1qrdlxjn8a9xmcyrn26vgr3y94uhhyr2nz8kr6y",
            "weight": 1
          },
          {
            "addr": "chronic1w9d7tqhh6hs3l5a2c6fehs096hxzkvxasxfedd",
            "weight": 1
          },
          {
            "addr": "chronic14vrvqa7xgczsj7xex4g23q5wj9yun0twk2v49s",
            "weight": 1
          },
          {
            "addr": "chronic1vx6ggt0h79wwmwjypj8phxnwza8amx3rhqk5ce",
            "weight": 1
          },
          {
            "addr": "chronic1smurszcxx8akwxg2cf0fz58pu850nte6e2nwc8",
            "weight": 1
          },
          {
            "addr": "chronic1rs4qkd8sq3uy6c95xkytqmxc9esudzthmf55gp",
            "weight": 1
          },
          {
            "addr": "chronic1hfqlpl2ukf93g5sm7h2q5pyejav6tztnuyjdal",
            "weight": 1
          },
          {
            "addr": "chronic1h2njl2fy7rtgnww995jnfn30w0nkm2sj5z2zqp",
            "weight": 1
          },
          {
            "addr": "chronic1dc3usgqvtkaar3j8t0g44zfedn6achcrl9jdwz",
            "weight": 1
          },
          {
            "addr": "chronic10ll8fgc8fl87e67ymt7z2dqc297k0y6xa53p2e",
            "weight": 1
          },
          {
            "addr": "chronic1uhm5zsv8zymdry20wfcmnacgftv538uk38u9x9",
            "weight": 1
          },
          {
            "addr": "chronic1a3ezd0rzucs652xacnfc5k8wuls6jn5ywvt5dn",
            "weight": 1
          },
          {
            "addr": "chronic1fgl0xcwxg6qcxrgwhqa4293peq46v7sv3zx0ms",
            "weight": 1
          },
          {
            "addr": "chronic1xrest8lraznmwpe84wd9e2eqkrhgf7efg5w4ak",
            "weight": 1
          },
          {
            "addr": "chronic1jem4rtcguk98nueysd6xy4satcszmafwu7g5yu",
            "weight": 1
          }
        ]
      }
    }
  }
  ``` 

## Smart Contract Details

### Code-id's

- cw4_group: 15
- cw4_voting: 13
- cw_proposal_single: 21
- cw_admin_factory: 32
- cw_core: 19 

### DAO Configuration

- Quorum: 50%
- Consensus Threshold: 49.99%
- Voting Time: 3 days (259200s)
