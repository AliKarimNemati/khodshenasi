<template>
  <header class="flex md:justify-center fixed top-0 w-full justify-end">
    <div
      class="flex md:justify-around md:w-[80%] w-full justify-between items-center"
    >
      <svg
        width="48"
        height="38"
        viewBox="0 0 48 38"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        class="md:m-2 m-5"
      >
        <rect
          x="0.631577"
          y="0.684326"
          width="47.3684"
          height="36.6316"
          fill="url(#pattern0)"
        />
        <defs>
          <pattern
            id="pattern0"
            patternContentUnits="objectBoundingBox"
            width="1"
            height="1"
          >
            <use
              xlink:href="#image0_1_280"
              transform="matrix(0.00148433 0 0 0.00191939 -0.00318621 0)"
            />
          </pattern>
          <image
            id="image0_1_280"
            width="678"
            height="521"
            xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAqYAAAIJCAYAAAB3Mf+kAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAADUHSURBVHgB7d0/rCXVneDxanol2AAtKzF042SbCCeDO3DgFcFCxkzAMtmMRprBkgMym4xNbEwyS2RwMOuRLBnLQpqRkAYTjJYInDBeydJ224mdtRMEIyExcuIl4G2d16/gvdfv3br3V6f+nHM+H+mqqt+7DzW3q+p+3zlVda90UJCbN28+lBaff/751/rlY1euXPlP/fLGyeMin5487hwdHf3+vvvuu5XWb/U6gI264Fj3X7q7x7mHTj1Ou9M53lGBKx1s2MnB+bn+IPvf+uVT3eUBGvF+/9+93R+83+6P2+93ACuZ+ViXYvVW/99+uz/e/UKosmXClM1JB+h+lODb/QjBU93dA/RS3k4H7l//+tc/7QBmdnKs+9v+WPdct+yxLo2o/ryP1DdEKlsjTNmM/iD9VH+w/F637AH6Iml04e3+zeL7/TH7TgeQ0cmx7tvd3WPdQ9260kjqa34hZyuEKas6NTr6nW79A/RF3j8J1Pc7gAk29Mv3RdIo6hv9KOpP/ULOmoQpq3niiSdSkL7cbTNIz0uB+k0HbOBQGw/S81Kgvt6PoL7WwQqEKYs7OUj/IK125XnDFD+wj/5Yd6M/1v2kKyNIz0uB+rIpfpZ2tYOFpGn7Rx555O/61R/1j+tdmVJMP3ft2rVPP/7449sdwAXSjFC/+Mf+8dWuTA+li7KuX79+49FHH7390UcffdrBAoyYsoiTUdI0cnCjq4fRU+CMwkdJL2P0lMUYMWV2/chBOrfqja6Mc0kPcTx62o8m/KIfTfioA5p28gv4e125o6SXOR497WeKun6m6BcdzMiIKbNJU/cnIwfPdZXr/z9fdLEAtCv9An5yMWftXAjKrIyYMouT6ax/7Ve/0TWgP1A/YzQB2tRH6Q/6Y8BLXRtudHdnin7uvFPmIEzJ7iRK03TWja4h6ZOq+jh9qI/TdzugCV/72td+0u/7L3RtOf74VHHKHEzlk1WrUXrOG7dv3/5mB1QtRWm/eL5r150+yp82rU9OwpRsROkZ4hQqJkq/IE7JSpiShSi9kDiFConSe4hTshGmTCZKdxKnUBFReilxShbClElE6V7EKVRAlI4Sp0wmTAkTpQcRp1AwUbo3ccokwpQQURoiTqFAovRg4pQwYcrBROkk4hQKIkrDxCkhwpSDiNIsxCkUQJROJk45mDBlb6I0K3EKGyZKsxGnHESYshdROgtxChskSrMTp+xNmDJKlM5KnMKGiNLZiFP2IkzZSZQuQpzCBojS2YlTRglTLiVKFyVOYUWidDHilJ2EKRcSpasQp7ACUbo4ccqlhCn3EKWrEqewIFG6GnHKhYQpZ4jSTRCnsABRujpxyj2EKV8QpZsiTmFGonQzxClnCFOOidJNEqcwA1G6OeKULwhTROm2iVPISJRuljjlmDBtnCgtgjiFDETp5olThGnLRGlRxClMIEqLIU4bJ0wbJUqLJE4hQJQWR5w2TJg2SJQWTZzCAURpscRpo4RpY0RpFcQp7EGUFk+cNkiYNkSUVkWcwg6itBritDHCtBGitEriFC4gSqsjThsiTBsgSqsmTuEUUVotcdoIYVo5UdoEcQqdKG2AOG2AMK2YKG2KOKVporQZ4rRywrRSorRJ4pQmidLmiNOKCdMKidKmiVOaIkqbJU4rJUwrI0rpxCmNEKXNE6cVEqYVEaWcIk6pmijlhDitjDCthCjlAuKUKolSzhGnFRGmFRCl7CBOqYoo5RLitBLCtHCilD2IU6ogShkhTisgTAsmSjmAOKVoopQ9idPCCdNCiVICxClFEqUcSJwW7GpHcUQpQTevXbvWffzxx7/ooBCilICH+sdzjz766M8/+uijTzuKIkwLI0qZoh9FeEqcUgpRygTitFDCtCCilBzEKSUQpWQgTgskTAshSslJnLJlopSMxGlhhGkBRClzEKfTpX3z+vXr6fGAN708RCkzEKcFcVX+xolS5tZvXy//+te//n7HXvp98qn+Nft2v/pUd/cN77T3+++90b+eP+04mChlZq7WL4Aw3TBRylLE6biT/TGF01N7PD29AX6zfwN8v2MvopSFiNONM5W/UaKUJZnW3+3U/nhzzx9JI6nP91OHd/qpw9sdO4lSFmRaf+Pu69gcURr3+OOPdz/+8Y+7Bx98sOMwfZy+/MQTT3yv44wp+2Oa1u9//m87LiVKY9IxLh3r0jGPgx3v02nf7tgcI6YbI0rjhih97LHHuieffLJ79913u88++6xjf0ZOz8q0Pz5n5PRiojRmiNL+F8numWee6T744IPuk08+6TiIkdONEqYbIkrjzo+UPvzww+I0SJzelXl/FKfniNKY8yOl999/vziNE6cbJEw3QpTGXTZ9L07jWo/TmfZHcXpClMZcNn0vTicRpxsjTDdAlMaNnVMqTuNajdOZ98fm41SUxoydUypOJxGnGyJMVyZK4/a90EmcxrUWp5H9MW1/B25XzcapKI3Z90IncTqJON0IYboiURp36NX34jSulTiN7I9pO/ynf/qn4yD41a9+1R2guTgVpTGHXn0vTicRpxsgTFciSuOit4QSp3G1x2k0Soft8Otf//rx18TpxURpTPSWUOJ0EnG6MmG6AlEaN/U+peI0rtY4nRqlA3F6MVEaM/U+peJ0EnG6ImG6MFEal+vm+eI0rrY4zRWlA3F6liiNyXXzfHE6iThdiTBdkCiNy/2JTuI0rpY4zR2lA3F6lyiNyf2JTuJ0EnG6AmG6EFEaN9fHjIrTuNLjdK4oHbQep6I0Zq6PGRWnk4jThQnTBYjSuLk/+16cxpUap3NH6aDVOBWlMXN/9r04nUScLkiYzkyUxs0dpQNxGldanC4VpYPW4lSUxswdpQNxOok4XYgwnZEojVsqSgfiNK6UOF06SgetxKkojVkqSgfidBJxugBhOhNRGrd0lA6GOH3rrbc6DrP1OF0rSge1x6kojVk6SgfidBJxOjNhOgNRGrdWlA5SnH7lK1/p3nvvvY7DbDVO147SQa1xKkpj1orSgTidRJzOSJhmJkrj1o7S038PcRqztTjdSpQOaotTURqzdpQOxOkk4nQmwjQjURq3lSgdiNO4rcTp1qJ0UEucitKYrUTpQJxOIk5nIEwzEaVxW4vSgTiNWztOtxqlg9LjVJTGbC1KB+J0EnGamTDNQJTGbTVKB+I0bq043XqUDkqNU1Eas9UoHYjTScRpRsJ0IlEat/UoHYjTuKXjtJQoHZQWp6I0ZutROhjiNN027w9/+EPHQcRpJsJ0AlEaV0qUDsRp3FJxWlqUDkqJU1EaU0qUDlKcPv3008fHOnF6MHGagTANEqVxpUXpQJzGzR2npUbpYOtxKkpjSovSQfp7i9MwcTqRMA0QpXGlRulAnMbNFaelR+lgq3EqSmNKjdKBOJ1EnE4gTA8kSuNKj9KBOI3LHae1ROlga3EqSmNKj9KBOJ1EnAYJ0wOI0rhaonQgTuNyxWltUTrYSpyK0phaonQgTicRpwHCdE+iNK62KB2I07ipcVprlA7WjlNRGlNblA7E6STi9EDCdA+iNK7WKB2I07honNYepYO14lSUxtQapQNxOok4PYAwHSFK42qP0oE4jTs0TluJ0sHScSpKY2qP0oE4nUSc7kmY7iBK41qJ0oE4jds3TluL0sFScSpKY1qJ0oE4nUSc7kGYXkKUxrUWpQNxGjcWp61G6WDuOBWlMa1F6UCcTiJORwjTC4jSuFajdCBO4y6L09ajdDBXnIrSmFajdCBOJxGnOwjTc0RpXOtROhCncefjVJSelTtORWlM61E6EKeTiNNLCNNTRGmcKD1LnMYNcdofsH8vSu+VK05FaYwoPUucTiJOLyBMT4jSOFF6MXEal+K0uxtN1/f9mZa2w6lxKkpjROnFxOkk4vQcYdqJ0ilE6W7idJIH9n1ii9thNE6vX7/+VFp2HESU7iZOJxGnpzQfpqI0TpTuR5zOq+XtMBinNzoOIkr3I04nEacnmg5TURonSg8jTudhOwzHKXsSpYcRp5OI067hMBWlcWIgRpzmZTv8kjidhyiNEaeTNB+nTYapKI0TA9OI0zxsh/cSp3mJ0mnE6SRNx2lzYSpK48RAHuJ0Gtvh5cRpHqI0D3E6SbNx2lSYitI4MZCXOI2xHY4Tp9OI0rzE6SRNxmkzYSpK48TAPMTpYWyH+xOnMaJ0HuJ0kubitIkwFaVxYmBe4nQ/tsPDidPDiNJ5idNJmorT6sNUlMaJgWWI091sh3HidD+idBnidJJm4rTqMBWlcWJgWeL0YrbD6cTpbqJ0WeJ0kibitNowFaVxYmAd4vQs22E+4vRionQd4nSS6uO0yjAVpXFiYF3i9C7bYX7i9CxRui5xOknVcVpdmIrSODGwDa3Hqe1wPuL0LlG6DeJ0kmrjtKowFaVxYmBbWo1T2+H8Wo9TUbot4nSSKuO0mjAVpXFiYJtai1Pb4XJajVNRuk3idJLq4rSKMBWlcWJg21qJU9vh8lqLU1G6beJ0kqritPgwFaVxYqAMtcep7XA9rcSpKC2DOJ2kmjgtOkxFaZwYKEutcWo7XF/tcSpKyyJOJ6kiTosNU1EaJwbKVFuc2g63o9Y4FaVlEqeTFB+nRYapKI0TA2WrJU5th9tTW5yK0rKJ00mKjtPiwlSUxomBOpQep7bD7aolTkVpHcTpJMXGaVFhKkrjxEBdSo1T2+H2lR6norQu4nSSIuO0mDAVpXFioE6lxantsBylxqkorZM4naS4OC0iTEVpnBioW0lx+vbbb9sOC5LiNG1Xn3zySVcCUVo3cTpJUXG6+TAVpXGitA2lxOn999//xUgc2/fOO+90b731VlcCUdoGcTpJMXG66TAVpXGitC0lxOkwLSxOty9F6Xe/+92uBKK0LeJ0kiLidLNhKkrjRGmbxCk5iFK2TpxOsvk43WSYitI4Udo2ccoUJUVp8rOf/UyUNkqcTrLpON1cmIrSuBQkf//3f989/PDDHe0Sp0SUFqWvvPJK9+STT3a0S5xOstk43VSYitK4FCJppDQtQZxyiBKj9Nlnn+1AnE6yyTjdTJiK0jhRykXEKfsQpZROnE6yuTjdRJiK0jhRyi7ilF1EKbUQp5NsKk5XD1NRGidK2Yc45SKilNqI00k2E6erhqkojROlHEKccpoopVbidJJNxOlqYSpK40QpEeKURJRSO3E6yepxukqYitI4UcoU4rRtopRWiNNJVo3TxcNUlMaJUnIQp21K/94vvfRSVwpRylTidJLV4nTRMBWlcaKUnMRpW373u991L774YvfZZ591JRCl5CJOJ1klThcLU1EaJ0qZgzhtQ4rSb33rW8W8KYtSchOnkywep4uEqSiNE6XMSZzWTZTCXeJ0kkXjdPYwFaVxopQliNM6iVI4S5xOsliczhqmojROlLIkcVoXUQoXE6eTLBKns4WpKI0TpaxBnNZBlMJu4nSS2eN0ljAVpXGilDWJ07KJUtiPOJ1k1jjNHqaiNE6UsgXitEyiFA4jTieZLU6zhqkojROlbIk4LYsohRhxOskscZotTEVpnChli8RpGUQpTCNOJ8kep1nCVJTGiVK2TJxumyiFPMTpJFnjdHKYitI4UZrfhx9+2L3zzjvdE0880ZGHON0mUcqbb77ZPfzww8dRxXTidJJscTopTEVpnCjNL0VpeqN+9913j//s3MN8xOm2iFJ+9KMfdT/84Q+P98kUU+I0D3E6SZY4DYepKI0TpfkNUZqWiXMP8xOn2yBKSVGaHknaDsRpXuJ0kslxGgpTURonSvM7H6UDcZqfOF2XKOV0lA7EaX7idJJJcXpwmIrSOFGa32VROhCn+YnTdYhSLorSgTjNT5xOEo7Tg8JUlMaJ0vzGonQgTvMTp8sSpeyK0oE4zU+cTjLE6U/7OP3jvj90UJheu3YtvQt9teMgojS/faN0IE7zE6fLEKXsE6UDcZqfOJ0kxek3Pv7445/u+wN7h+kTTzzxgytXrjzXcRBRmt+hUToQp/mJ03mJUg6J0oE4zU+cTnKjH9h8qI/Td/d58l5h2kfp9/oofanjIKI0v2iUDsRpfuJ0HqKUSJQOxGl+4jSub8hv9HH6732c/nLsuaNhms4r7RdvdxxElOY3NUoH4jQ/cZqXKGVKlA7EaX7iNC7F6aOPPvruR71dz9sZpn2UPnR0dPSv3d1zBNiTKM0vV5QOxGl+4jQPUUqOKB2I0/zEadgD/eOZsYuhdobpI4888nd94T7TsTdRml/uKB2I0/zE6TSilJxROhCn+YnTsDTg+cCu800vDdOTKfx/7NibKM1vrigdiNP8xGmMKGWOKB2I0/zEaczJlP4v+lHTOxd9/9IwvXbt2v/tTOHvTZTmN3eUDsRpfuL0MKKUOaN0MMRp+re7//77O6YTp2E3LruF1IVh+qd/+qfP90X7fMdeRGl+S0XpQJzmJ073I0pZIkoHaTv74IMPumeeeUacZiJOQ270o6a3+1HT357/xoVh2j/5nzujpXsRpfktHaUDcZqfON1NlLJklA4++eQTcZqZOA1JN95//fwX7wlTo6X7E6X5rRWlA3Ganzi9mChljSgdiNP8xOnBHrp27dqdPk5vn/7iPWFqtHQ/ojS/taN0IE7zE6dniVLWjNKBOM1PnB6mHwhN55r+w+mvnQlTo6X7EaX5bSVKB+I0P3F6lyhlC1E6EKf5idODXD9/hf6ZMO2/+YN+caPjUqI0v61F6UCc5td6nIpSthSlA3Ganzg9yJkr9L8I05P7lr7WcSlRmt9Wo3QgTvNrNU5FKVuM0oE4zU+c7i1dof/68GlQX4TpI4888rxPebqcKM1v61E6EKf5tRanopQtR+lAnOYnTvdzdHTUD5p+/Mu0/kWYXr9+/X+lRcc9RGl+pUTpQJzm10qcilJKiNKBOM1PnI7rB0YfGKbzj8P0ZBr/f3bcQ5TmV1qUDsRpfrXHqSilpCgdiNP8xOmoL6bzj8P0T/7kT57ra/W5jjNEaX6lRulAnOZXa5yKUkqM0oE4zU+c7vb555//7t/+7d9uHYdpX6nf6xdf7fiCKM2v9CgdiNP8aotTUUrJUToQp/mJ08v1A6Sf9tP5Pz8O0+vXr6dpfDfVPyFK86slSgfiNL9a4lSUUkOUDsRpfuL0Ug+ljyi9enJ+6csdx0RpfrVF6UCc5ld6nIpSaorSgTjNT5xe6KF0nunVfrT0Zv+H5ztE6QxqjdKBOM2v1DgVpdQYpQNxmp84vVc/nf/Lq4888shz7l8qSudQe5QOxGl+KU6T4bXdotP/7qKUmqN0IE7zE6dnHR0d/Z+r165de6EP05tdw0Rpfq1E6UCc5je8lluP0xSlKUhEabtaiNKBOM1PnH6p79GP0lT+t/v1G12jRGl+rUXpQJzmV0Kc3rlzp/vss8+6EojS/FqK0oE4zU+c3tWPmP4+hel3ukY/8UmU5tdqlA7EaX4lxGkJRGl+LUbpQJzmJ06PR0z/mML0pa7BW0WJ0vxaj9KBOM1PnE4jSvNrOUoH4jQ/cdodh+lrXWNEaX6i9Cxxmp84jRGl+YnSL4nT/FqP0xSmL3cNEaX5idKLidP8xOlhRGl+ovRe4jS/huP0gebCNEXpY4891pHPiy++eHxlMvcSp/ml1zL9EmSb2+2FF17o/vqv/7ojH1F6uRSn6ULAFKfkkeI0He/eeuutriXNhelvfvMbv9VllnYct7m4nDjNKwXpD3/4w2KuhF9Lep2efPLJ7uGHH+6YTpTulmYhX3311eOYIo/0npoGflL0t6S5MDXlkJ+TtceJ0zxKu5H9mlK4v/vuu+I0A1G6m1Pk8kvHuHSsa3FmKIXp811jV+WL0/zE6ThxOo0oPZw4nU6U7iZK82s5Snt3hvuYNne7KHGanzgdJ05jRGmcOI0TpbuJ0vwaj9LkOEyf6le+2jVInOYnTseJ08OI0unE6eFE6W6iND9Reuy3V69du/ZnV65cudk1SpzmJ07HidP9iNJ8xOn+ROluojQ/UfqF91OY3ujDtOn7O4jT/MTpOHG6myjNT5yOE6W7idL8ROmXjo6Ofn71kUceud6H6V92jROn+YnTceL0YqJ0PuL0cqJ0N1Ganyg967777nvtar+B/bFf/06HOJ2BOB0nTs8SpfMTp/cSpbuJ0vxE6b36gdJXr3700UefnlyZ/0CHOJ2BOB0nTu8SpcsRp18SpbuJ0vxE6YU+vX379otX01ofpt/oGr0y/yLiND9xOq71OBWlyxOnonSMKM1PlF7s6Ojo3Y8//vgfj8P02rVrj7Z+AdR54jQ/cTqu1TgVpetpOU5F6W6iND9RutM/9GH6y/vS2n333fd2xz28WebnQDeutTdL+9n6WnyzFKW7OVbnJ0p361v0/bQ8HjE9Oc/0+a7BT4AaY+Q0PyOn41oZORWl29HSyKko3U2U5idKR925ffv2/0grV4ev9NP5/7mfzn+q4x7iND9xOq72OBWl29NCnIrS3URpfqJ03NHR0U/7afz/nda/CNNHH330Tue2UZcSp/mJ03G1xqko3a6a41SU7iZK8xOl++mn8f8qzd6n9S/C9GQ6/6l+9UbHhcRpfuJ0XG1xKkq3r8Y4FaW7idL8ROnebvXT+K8Of7h6+jv9qOm/94vmPwVqF3GanzgdV0ucitJy1BSnonQ3UZqfKN3flStXXuoHR28Pfz4Tpv03futm++PEaX7idFzpcSpKy1NDnIrS3URpfqL0IOmip2+e/sLV88+4du3af3QR1Dhxmp84HVdqnIrScpUcp6J0N1Ganyg9TN+br/eDou+f/to9YdpP59/qFy90Rk1HpThNjxRT5CFOx5UWp6K0fCXGqSjdTZTmJ0oPdqcP0xeHi54G94Rp/4Q/9nH6//pVnwS1h7QBfvjhh+I0I3E6rpQ4FaX1KClOReluojQ/UXq4NFp669atez7g6epFT+7j9JduuL8/cZqfOB239TgVpfUpIU5F6W6iND9RGpLOLf2Li75x9bKf6EdN0xVSz3fsRZzmJ07HbTVORWm9thynonQ3UZqfKI3pR0u/c/pK/NMuDdP+B+6cfBrUNzr2Ik7zE6fjthanorR+KU7TxZ9p30z76BaI0t1EaX6iNOyNfrT0+5d98+qun+xHTX/Z3b2vqSn9PYnT/MTpuK3EqShtR/o3TvvkFuJUlO4mSvMTpWHpgqdvnr/g6bSdYXpyIZQp/QOJ0/zE6bi141SUtmcLcSpKdxOl+YnSuDSFf+vWrV/ses7OME3SlH4fp1f61ac69iZO8xOn49aKU1HarjXjVJTuJkrzE6VxfZR+v4/S18eeNxqmSbr56fXr15/qV2907E2c5idOxy0dp6KUNeJUlO4mSvMTpZPcun379l/t88S9wjTpR01/3jnf9GDiND9xOm6pOBWlDJaMU1G6myjNT5ROks4r/bNd55WetneYnpxvmuL0uU6cHkSc5idOx80dp6KU85aIU1G6myjNT5ROkqL06X4K/86+P7B3mCapdsVpjDjNT5yOmytORSmXmTNOReluojQ/UTrJp32U/tdDojQ5KEwTcRonTvMTp+Nyx6koZcwccSpKdxOl+YnSST49GSn9bXegg8M0Eadx4jQ/cTouV5yKUvaVM05F6W6iND9ROskQpbe6gFCYJuI0TpzmJ07HTY1TUcqhcsSpKN1NlOYnSieZFKVJOEwTcRonTvMTp+OicSpKiZoSp6J0N1GanyidZHKUJpPCNBGnceI0P3E67tA4FaXjXnnlle7xxx//4rXlrEicitLdRGl+onSSLFGaTA7TRJzGidP8xOm4feNUlI5LUfrss89+8VqK04sdEqeidDdRmp8onSRblCZZwjQRp3HiND9xOm4sTkXpuCFKB+J0t33iVJTuJkrzE6WTZI3SJFuYJuI0TpzmJ07HXRanonTc+SgdiNPddsWpKN1NlOYnSifJHqVJ1jBNxGlc2jHS48knn+zuv//+junE6bjzcSpKx10WpQNxuttFcSpKdxOl+YnSSWaJ0iR7mCbiNO7OnTvdBx980D3zzDPiNBNxOm4IqPRaidLdxqJ0IE53Ox2nb775pijdQZTmJ0onmS1KkyvdjG7evHnj6OjovX71RsdB0hW+6UA01+dNt8hI4Li0vXl9LvfCCy8cPw5hJHA329xuojQ/UTrJrFGazDJiOjByGvfJJ58YOc3s4YcfPj5N4t133+0+++yzjnt5XS4XidLEyOlutrnLidL8ROkks0dpMmuYJuI0TpzmJ06JiEbpQJxyKFGanyidZJEoTWYP00ScxonT/MQph5gapQNxyr5EaX6idJLFojRZJEwTcRonTvMTp+wjV5QOxCljRGl+onSSRaM0WSxME3EaJ07zE6fskjtKB+KUy4jS/ETpJItHabJomCbiNE6c5idOuchcUToQp5wnSvMTpZOsEqXJ4mGaiNM4cZqfOOW0uaN0IE4ZiNL8ROkkq0VpskqYJuI0LsXpb37zm71u8s1+xCnJUlE6EKeI0vxE6SSrRmmyWpgm4jTuww8/PH6kT00hD3HatqWjdCBO2yVK8xOlk6wepcmqYZqI07i044nTvMRpm9aK0oE4bY8ozU+UTrKJKE1WD9NEnMaJ0/zEaVvWjtKBOG2HKM1PlE6ymShNNhGmiTiNE6f5idM2bCVKB+K0fqI0P1E6yaaiNNlMmCbiNE6c5idO67a1KB2I03qJ0vxE6SSbi9JkU2GaiNM4cZqfOK3TVqN0IE7rI0rzE6WTbDJKk82FaSJO48RpfuK0LluP0oE4rYcozU+UTrLZKE02GaaJOI0Tp/mJ0zqUEqUDcVo+UZqfKJ1k01GabDZME3EaJ07zE6dlKy1KB+K0XKI0P1E6yeajNNl0mCbiNE6c5idOy1RqlA7EaXlEaX6idJIiojTZfJgm4jROnOYnTstSepQOxGk5RGl+onSSYqI0KSJME3EaJ07zE6dlqCVKB+J0+0RpfqJ0kqKiNCkmTBNxGidO8xOn21ZblA7E6XaJ0vxE6STFRWlSVJgm4jROnOYnTrep1igdiNPtEaX5idJJiozSpLgwTcRpnDjNT5xuS+1ROhCn2yFK8xOlkxQbpUmRYZqI0zhxmp843YZWonQgTtcnSvMTpZMUHaVJsWGaiNM4cZqfOF1Xa1E6EKfrEaXz+Ju/+RtRGlN8lCZFh2kiTuPEaX7idB2tRulAnC5PlM7ju9/9bvfBBx90HKyKKE2KD9NEnMaJ0/zE6bJaj9KBOF2OKJ1HitJ33nmn42DVRGlSRZgm4jROnOYnTpchSs8Sp/MTpfMQpWFVRWlSTZgm4jROnOYnTuclSi8mTucjSuchSsOqi9KkqjBNxGmcOM1PnM5DlO4mTvMTpfMQpWFVRmlSXZgm4jROnOYnTvMSpfsRp/mI0nmI0rBqozSpMkwTcRonTvMTp3mI0sOI0+lE6TxEaVjVUZpUG6aJOI0Tp/mJ02lEaYw4jROl8xClYdVHaVJ1mCbiNE6c5idOY0TpNOL0cKJ0HqI0rIkoTaoP00ScxonT/MTpYURpHuJ0f6J0HqI0rJkoTZoI00ScxonT/FKcPvbYY8dxyuVEaV7idJwonYcoDWsqSpNmwjQRp3HiNK/0Wr700kvdH/7wh46LidJ5iNPLidJ5iNKw5qI0aSpME3EaJ07zSK/ht771reMlFxOl8xKn9xKl8xClYU1GadJcmCbiNE6cTiNKx4nSZYjTL4nSeYjSsGajNGkyTBNxGidOY0TpOFG6LHEqSuciSsOajtKk2TBNxGmcOD2MKB0nStfRcpyK0nmI0rDmozRpOkyTU3H6fP94oGNv4nQ/onScKF1Xi3EqSuchSsNE6YnmwzQ5idN0356/7MTpQcTpbqJ0nCjdhpbiVJTOQ5SGidJThOmJPk4/Eqcx4vRionScKN2WFuJUlM5DlIaJ0nOE6SniNE6cniVKx4nSbao5TkXpPERpmCi9gDA9R5zGidO7ROk4UbptNcapKJ2HKA0TpZcQphcQp3Gtx6koHSdKy1BTnD744IPdz372M1GamSgNE6U7CNNLiNO4VuNUlI4TpWWpIU5TlKaR0scee6wjH1EaJkpHCNMdxGlca3EqSseJ0jKVHKdDlD7++OMd+YjSMFG6B2E6QpzGtRKnonScKC1biXEqSuchSsNE6Z6E6R7EaVztcSpKx4nSOpQUp6J0HqI0TJQeQJjuSZzG1RqnonScKK1LCXEqSuchSsNE6YGE6QHEaVxtcSpKx4nSOm05TkXpPERpmCgNEKYHEqdxtcSpKB0nSuu2xTgVpfMQpWGiNEiYBojTuNLjVJSOE6Vt2FKcitJ5iNIwUTqBMA0Sp3GlxqkoHSdK27KFOBWl8xClYaJ0ImE6gTiNKy1ORek4UdqmNeNUlM5DlIaJ0gyE6UTiNK6UOBWl40Rp29aIU1E6D1EaJkozEaYZiNO4rcepKB0nSkmWjFNROg9RGiZKMxKmmYjTuK3GqSgdJ0o5bYk4FaXzEKVhojQzYZqROI3bWpyK0nGilIvMGaeidB6iNEyUzkCYZiZO47YSp6J0nChllzniVJTOQ5SGidKZCNMZiNO4teNUlI4TpewjZ5yK0nmI0jBROiNhOhNxGrdWnIrScaKUQ+SIU1E6D1EaJkpnJkxnJE7jlo5TUTpOlBIxJU5F6TxEaZgoXYAwnZk4jVsqTkXpOFHKFJE4FaXzEKVhonQhwnQB4jRu7jgVpeNEKTkcEqeidB6iNEyULkiYLkScxs0Vp6J0nCglp33iVJTOQ5SGidKFCdMFidO43HEqSseJUuawK05F6TxEaZgoXYEwXZg4jcsVp6J0nChlThfFqSidhygNE6UrEaYrEKdxU+NUlI4TpSzhdJyK0nmI0jBRuiJhuhJxGheNU1E6TpSypCFOv/3tb4vSzERpXB+lf9U36fsdq7jSsaqbvaOjo/f61Yc6DvLss892r7zyyl7PFaXjRCnUQZTG9VH6zT5K3+hYjRHTlRk5jdt35FSUjhOlUAdRGidKt0GYboA4jRuLU1E6TpRCHURpnCjdDmG6EeI07rI4FaXjRCnUQZTGidJtEaYbIk7jzsepKB0nSqEOojROlG6PMN0YcRo3xGm6uleU7iZKoQ6iNE6UbpOr8jfK1frMRZTmN4RBulMELEWUxonS7foPHZuUbuzbt+nT4pScRGl+KQxSIAzEKUsQpXGidNtM5W+YaX1yEqX5nY/S9957r/vKV77iZvHMSpTGidLtE6YbJ07JQZTmdz5KB+KUOYnSOFFaBmFaAHHKFKI0v8uidCBOmYMojROl5RCmhRCnRIjS/MaidCBOyUmUxonSsgjTgohTDiFK89s3SgfilBxEaZwoLY8wLYw4ZR+iNL9Do3QgTplClMaJ0jIJ0wKJU3YRpflFo3QgTokQpXGitFzCtFDilIuI0vymRulAnHIIURonSssmTAsmTjlNlOaXK0oH4pR9iNI4UVo+YVo4cUoiSvPLHaUDccouojROlNZBmFZAnLZNlOY3V5QOxCkXEaVxorQewrQS4rRNojS/uaN0IE45TZTGidK6CNOKiNO2iNL8lorSgTglEaVxorQ+wrQy4rQNojS/paN0IE7bJkrjRGmdhGmFxGndRGl+a0XpQJy2SZTGidJ6CdNKidM6idL81o7SgThtiyiNE6V1E6YVE6d1EaX5bSVKB+K0DaI0TpTWT5hWTpzWQZTmt7UoHYjTuonSOFHaBmHaAHFaNlGa31ajdCBO6yRK40RpO4RpI8RpmURpfluP0oE4rYsojROlbRGmDRGnZRGl+ZUSpQNxWgdRGidK2yNMGyNOyyBK8ystSgfitGyiNE6UtkmYNkicbpsoza/UKB2I0zKJ0jhR2i5h2ihxuk2iNL/So3QgTssiSuNEaduEacPE6baI0vxqidKBOC2DKI0TpQjTxonTbRCl+dUWpQNxum2iNE6UkghTxOnKRGl+tUbpQJxukyiNE6UMhCnHxOk6RGl+tUfpQJxuiyiNE6WcJkz5gjhdlijNr5UoHYjTbRClcaKU84QpZ4jTZYjS/FqL0oE4XZcojROlXESYcg9xOi9Rml+rUToQp+sQpXGilMsIUy4kTuchSvNrPUoH4nRZojROlLKLMOVS4jQvUZqfKD1LnC5DlMaJUsYIU3YSp3mI0vxE6cXE6bxEaZwoZR9XOtjDzd7R0dF7/epDHQf5+te/3v34xz/uyOfDDz/s/vzP/7zjYg8++GD3L//yL8dL8hGlcaKUfRkxZS9GTuNSRCUpUMkjBVcaFUyjg5yVXpv0i1B6fchHlMaJUg4hTNmbOI371a9+dbwUp/mkqWpxetYQpabx8xKlcaKUQwlTDiJO48RpfuL0S6J0HqI0TpQSIUw5mDiNE6f5iVNROhdRGidKiRKmhIjTOHGaX8txKkrnIUrjRClTCFPCxGmcOM2vxTgVpfMQpXGilKmEKZOI0zhxml9LcSpK5yFK40QpOQhTJhOnceI0vxbiVJTOQ5TGiVJyEaZkIU7jxGl+NcepKJ2HKI0TpeQkTMlGnMaJ0/xqjFNROg9RGidKyU2YkpU4jROn+dUUp6J0Hj/60Y+6N998s+NwopQ5CFOyE6dx4jS/GuJUlM4jRWl6cDhRylyEKbMQp3HiNL+S41SUzkOUxolS5iRMmY04jROn+ZUYp6J0HqI0TpQyN2HKrMRpnDjNr6Q4FaXzEKVxopQlCFNmJ07jxGl+JcSpKJ2HKI0TpSxFmLIIcRonTvPbcpyK0nmI0jhRypKEKYsRp3HiNL8txqkonYcojROlLE2YsihxGidO89tSnIrSeYjSOFHKGoQpixOnceI0vy3EqSidhyiNE6WsRZiyCnEaJ07zWzNORek8RGmcKGVNwpTViNM4cZrfGnEqSuchSuNEKWsTpqxKnMaJ0/yWjFNROg9RGidK2QJhyurEaZw4zW+JOBWl8xClcaKUrRCmbMJJnP6uuxunHECc5jdnnIrSeYjSOFHKlghTNqNv09/2cfr7fvW5joOI0/zmiFNROg9RGidK2Rphyqb0cXpLnMaI0/xyxqkonYcojROlbJEwZXPEaZw4zS9HnIrSeYjSOFHKVglTNkmcxonT/KbEqSidhyiNE6VsmTBls8RpnDjNLxKnonQeojROlLJ1wpRNE6dx4jS/Q+JUlM5DlMaJUkogTNk8cRonTvPbN05fffVVr3tmojROlFIKYUoRxGmcOM1vLE5feeWV7plnnunIR5TGiVJKIkwphjiNE6f5XRanKUqfffbZjnxEaZwopTTClKKI0zhxmt/5OBWl+YnSOFFKiYQpxRGnceI0vyFOn376aVGamSiNE6WUSphSJHEaJ07zS3Hq6vu8RGmcKKVkwpRiidM4ccqWidI4UUrphClFE6dx4pQtEqVxopQaCFOKJ07jxClbIkrj+ij9fh+lr3VQOGFKFcRpnDhlC0Rp3EmUvtxBBYQp1RCnceKUNYnSOFFKbYQpVRGnceKUNYjSOFFKjYQp1RGnceKUJYnSOFFKrYQpVRKnceKUJYjSOFFKzYQp1RKnceKUOYnSOFFK7YQpVROnceKUOYjSOFFKC4Qp1ROnceKUnERpnCilFcKUJojTOHFKDqI0TpTSEmFKM8RpnDhlClEaJ0ppjTClKeI0TpwSIUrjRCktEqY0R5zGiVMOIUrjRCmtEqY0SZzGiVP2IUrjRCktE6Y0S5zGiVN2EaVxopTWCVOaJk7jxCkXEaVxohSEKYjTCcQpp4nSOFEKdwlT6MTpFOKURJTGiVL4kjCFE+I0Tpy2TZTGiVI4S5jCKeI0Tpy2SZTGiVK4lzCFc8RpnDhtiyiNE6VwMWEKFxCnceK0DaI0TpTC5YQpXEKcxonTuonSOFEKuwlT2EGcxonTOonSOFEK44QpjBCnceK0LqI0TpTCfoQp7EGcxonTOojSOFEK+xOmsCdxGidOyyZK40QpHEaYwgHEaZw4LZMojROlcDhhCgcSp3HitCyiNE6UQowwhQBxGidOyyBK40QpxAlTCBKnceJ020RpnCiFaYQpTCBO48TpNonSOFEK0wlTmEicxonTbRGlcaIU8hCmkIE4jROn2yBK40Qp5CNMIRNxGidO1yVK40Qp5CVMISNxGidO1yFK40Qp5CdMITNxGidOlyVK40QpzEOYwgzEaZw4XYYojROlMB9hCjMRp3HidF6iNE6UwryEKcxInMaJ03mI0jhRCvMTpjAzcRonTvMSpXGiFJYhTGEB4jROnOYhSuNEKSxHmMJCxGmcOJ1GlMaJUliWMIUFidM4cRojSuNEKSxPmMLCxGmcOD2MKI0TpbAOYQorEKdx4nQ/ojROlMJ6hCmsRJzGidPdRGmcKIV1CVNYkTiNE6cXE6VxohTWJ0xhZeI0TpyeJUrjRClsgzCFDRCnceL0LlEaJ0phO4QpbIQ4jWs9TkVpnCiFbRGmsCHiNK7VOBWlcaIUtkeYwsaI07jW4lSUxolS2CZhChskTuNaiVNRGidKYbuEKWyUOI2rPU5FaZwohW0TprBh4jSu1jgVpXGiFLZPmMLGidO42uJUlMaJUiiDMIUCiNO4WuJUlMaJUiiHMIVCiNO40uNUlMaJUiiLMIWCiNO4UuNUlMaJUiiPMIXCiNO40uJUlMaJUiiTMIUCidO4UuJUlMaJUiiXMIVCidO4rcepKI0TpVA2YQoFE6dxW41TURonSqF8whQKJ07jthanojROlEIdhClUQJzGbSVORWmcKIV6CFOohDiNWztORWmcKIW6CFOoiDiNWytORWmcKIX6CFOojDiNWzpORWmcKIU6CVOokDiNWypORWmcKIV6CVOolDiNmztORWmcKIW6CVOomDiNmytORWmcKIX6CVOonDiNyx2nojROlEIbhCk0QJzG5YpTURonSqEdwhQaIU7jpsapKI0TpdAWYQoNEadx0TgVpXGiFNojTKEx4jTu0DgVpXGiFNokTKFB4jRu3zgVpXGiFNolTKFR4jRuLE5FaZwohbYJU2iYOI27LE5FaZwoBYQpNE6cxp2PU1EaJ0qBRJgC4nSCIU7TUpTGiFJgcKUDOHHz5s3nj46OftLBQkQpcJoRU+ALRk5ZkigFzhOmwBnilCWIUuAiwhS4x0mcplN9nuogM1EKXEaYAhfq4/R9cUpuohTYRZgClxKn5CRKgTHCFNhJnJKDKAX2IUyBUeKUKUQpsC9hCuxFnBIhSoFDCFNgb+KUQ4hS4FDCFDiIOGUfohSIEKbAwcQpu4hSIEqYAiHilIuIUmAKYQqEiVNOE6XAVMIUmESckohSIAdhCkwmTtsmSoFchCmQhThtkygFchKmQDbitC2iFMhNmAJZidM2iFJgDsIUyE6c1k2UAnMRpsAsxGmdRCkwJ2EKzEac1kWUAnMTpsCsxGkdRCmwBGEKzE6clk2UAksRpsAixGmZRCmwJGEKLEaclkWUAksTpsCixGkZRCmwBmEKLE6cbpsoBdYiTIFViNNtEqXAmoQpsBpxui2iFFibMAVWJU63QZQCWyBMgdWJ03WJUmArhCmwCeJ0HaIU2BJhCmyGOF2WKAW2RpgCmyJOlyFKgS0SpsDmiNN5iVJgq4QpsEnidB6iFNgyYQpsljjNS5QCWydMgU0Tp3mIUqAEwhTYPHE6jSgFSiFMgSKI0xhRCpREmALFEKeHEaVAaYQpUBRxuh9RCpRImALFEae7iVKgVMIUKJI4vZgoBUomTIFiidOzRClQOmEKFE2c3iVKgRoIU6B4rcepKAVqIUyBKpzE6e/71ee6hvRR+s0+Sl/rACpwpQOoyM3e0dHRP/erN7q6fdpH6V/0Ufp+B1AJYQpUp2/TG32cvtfVG6e3TqL0TgdQEVP5QHX6af1PP/7449drPO+0D9LXT6bvP+oAKmPEFKhaP3r6VD96+pOu/NHTOydB+n4HUClhCjShD9SX+0D9XleedC7p6/3ytT5KP+0AKiZMgWakc08///zzl/vQ+9uuDG/3f9cXnUsKtEKYAs0pIFDfP7k36fsdQEOEKdCsU4H637r1z0E1ZQ80T5gCdMeR+lwfqc/1cfjf+z8+1C0jBWiarv+p0VEAYQpwj3Ql/0mkfq3Lf7up94+Ojm7fd999b/frt4yOAnxJmAKMSKHaLx7qY/XmSaymEdUbJ8vzo6ufnnrc6iP03/sIvZXW+8cdIQpwuf8PaVlRwkddMLwAAAAASUVORK5CYII="
          />
        </defs>
      </svg>

      <!-- laptop mode -->
      <div class="container md:flex hidden justify-between">
        <ul class="flex mt-5">
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4 font-semibold"
              >آغاز</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 border-t-4 border-[#2c9564] py-3 px-4 font-semibold"
              >چرا خودشناسی</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4 font-semibold"
              >منتخب صوت</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4"
              >جلسات</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4 font-semibold"
              >منتخب متن</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4 font-semibold"
              >شبکه‌های اجتماعی</a
            >
          </li>
          <li>
            <a
              href="#"
              class="text-sm hover:text-[#2c9564] mt-5 hover:border-t-4 hover:border-[#2c9564] py-3 px-4 font-semibold"
              >سوالات متداول</a
            >
          </li>
        </ul>
        <div class="relative">
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="absolute top-5 right-2"
          >
            <g clip-path="url(#clip0_1_291)">
              <path
                d="M15.5 14H14.71L14.43 13.73C15.41 12.59 16 11.11 16 9.5C16 5.91 13.09 3 9.5 3C5.91 3 3 5.91 3 9.5C3 13.09 5.91 16 9.5 16C11.11 16 12.59 15.41 13.73 14.43L14 14.71V15.5L19 20.49L20.49 19L15.5 14ZM9.5 14C7.01 14 5 11.99 5 9.5C5 7.01 7.01 5 9.5 5C11.99 5 14 7.01 14 9.5C14 11.99 11.99 14 9.5 14Z"
                fill="#CCCCCC"
              />
            </g>
            <defs>
              <clipPath id="clip0_1_291">
                <rect width="24" height="24" fill="white" />
              </clipPath>
            </defs>
          </svg>

          <input
            type="text"
            class="border border-gray-200 focus:border-[#2c9564] outline-none rounded-3xl text-xs bg-[#fafafa] p-3 w-64 mb-4 mt-3 pr-8"
            placeholder="جستجو"
          />
        </div>
      </div>

      <!-- mobile mode -->
      <div class="md:hidden flex-col">
        <button class="m-5" @click="openMenu = true" v-if="!openMenu">
          <span class="border-2 border-black block w-10 mt-2"></span>
          <span class="border-2 border-black block w-10 mt-2"></span>
          <span class="border-2 border-black block w-10 mt-2"></span>
        </button>

        <div v-if="openMenu" class="h-screen left-0 fixed w-1/2 top-0">
          <div class="relative m-3">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="absolute top-5 right-2"
            >
              <g clip-path="url(#clip0_1_291)">
                <path
                  d="M15.5 14H14.71L14.43 13.73C15.41 12.59 16 11.11 16 9.5C16 5.91 13.09 3 9.5 3C5.91 3 3 5.91 3 9.5C3 13.09 5.91 16 9.5 16C11.11 16 12.59 15.41 13.73 14.43L14 14.71V15.5L19 20.49L20.49 19L15.5 14ZM9.5 14C7.01 14 5 11.99 5 9.5C5 7.01 7.01 5 9.5 5C11.99 5 14 7.01 14 9.5C14 11.99 11.99 14 9.5 14Z"
                  fill="#CCCCCC"
                />
              </g>
              <defs>
                <clipPath id="clip0_1_291">
                  <rect width="24" height="24" fill="white" />
                </clipPath>
              </defs>
            </svg>

            <input
              type="text"
              class="border border-gray-200 focus:border-[#2c9564] outline-none rounded-3xl text-xs bg-[#fafafa] p-3 w-44 mb-4 mx-auto mt-3 pr-8"
              placeholder="جستجو"
            />
          </div>
          <ul class="flex mt-5 flex-col">
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >آغاز</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 border-r-4 border-[#2c9564] py-3 px-4"
              >چرا خودشناسی</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >منتخب صوت</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >جلسات</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >منتخب متن</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >شبکه‌های اجتماعی</a
            >
            <a
              href="#"
              class="hover:text-[#2c9564] mt-2 hover:border-r-4 hover:border-[#2c9564] py-3 px-4"
              >سوالات متداول</a
            >
          </ul>
        </div>
        <div
          v-if="openMenu"
          @click="openMenu = false"
          class="fixed right-0 bg-black w-1/2 h-screen opacity-50 top-0"
        ></div>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from "vue";
let openMenu = ref(false);
</script>