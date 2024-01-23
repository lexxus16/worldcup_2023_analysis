# World Cup 2023 Analysis

This project was developed during my internship at Mentorness. The main objective of this EDA is to extract meaningful insights and patterns to gain a deeper understanding of the tournament's dynamics. The EDA process involves statistical and visual exploration of various aspects of the dataset, such as team performances, player statistics, and match outcomes.

Key components of this exploratory data analysis include:

1. Team Performance Analysis
2. Player Statistics Exploration
3. Match Outcome Trends
4. Temporal Analysis

## About Dataset

The dataset offers a comprehensive array of cricket-related attributes and an in-depth analysis of the World Cup 2023. Each entry is characterized by the following columns:

- **team:** The participating cricket team.
- **player:** Individual player's name.
- **bat_or_bowl:** Indicates whether the entry corresponds to batting or bowling.
- **bb_bf:** Number of balls bowled or faced.
- **runs:** Runs scored.
- **wkts:** Wickets taken.
- **wicketball_prob:** Probability of taking a wicket with a ball.
- **runs_per_ball:** Average runs scored per ball.
- **opposition:** Opposing team.
- **ground:** Venue of the match.
- **start_date:** Date of the match.
- **overs:** Number of overs played.
- **mdns:** Maidens bowled.
- **econ:** Economy rate.
- **inns:** Innings played.
- **4s:** Fours scored.
- **6s:** Sixes scored.
- **sr:** Strike rate.
- **not_out:** Indicates whether the player remained not out.
- **mins:** Minutes spent on the field.

Dataset Statistics are as follows:

<p align="center">
  <img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/e6c900de-f536-4e57-9851-bb28d7ebc972" alt="Alt Text" width="880"/>
</p>

## Team Performance Analysis
### Bowling

<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/6924f0e0-2d24-4748-8de5-ef3ea6496032" alt="Image 1" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/e88857e6-a830-43e1-b649-4d7e0ea7de05" alt="Image 2" width="300" height="300"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/06d082c6-d602-43cb-9e1f-62ed7a2dd33f" alt="Image 3" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/5025bc26-2fc6-4f68-ba3d-f49de9191a64" alt="Image 4" width="300" height="300"></td>
    </tr>
  </table>
</div>

**Wickets:**
India emerged as the leading wicket-taker with 94 wickets, followed by South Africa with 88 and Australia with 77. In contrast, Sri Lanka had the lowest wicket count at 50.

**Overs Bowled:**
New Zealand and Australia showcased remarkable bowling endurance, delivering 499 and 448 overs, respectively. In contrast, Sri Lanka bowled the fewest overs, totaling 375.

**Economy and Maidens:**
India exhibited the most economical bowling performance with an impressive economy rate of 4.9, closely followed by Australia. On the flip side, Sri Lanka and Pakistan faced challenges with their economy rates, ranking among the least favorable. Additionally, the Indian bowling unit delivered the highest number of maidens in the tournament.

*In conclusion, the bowling analysis highlights India's dominance, establishing them as the premier bowling unit in the World Cup.*

### Batting

<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/89793214-a835-47ff-909c-3c993f573da7" alt="Image 1" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/2a22ee5e-84d8-4315-b586-3281ea676192" alt="Image 2" width="300" height="300"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/f42990a1-6ee7-4174-98b9-2999bd1f2235" alt="Image 3" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/398a7459-76e0-49c8-ac5c-ed94a1bd33fb" alt="Image 4" width="300" height="300"></td>
    </tr>
  </table>
</div>

**Top Scorers:**
India, South Africa, and Australia emerged as the top three teams with run totals of 2810, 2773, and 2772, respectively. In contrast, Netherlands recorded a total of 1728 runs.

**Strike Rate:**
India, South Africa, and New Zealand showcased impressive strike rates of 100, 98, and 97, respectively. Notably, Australia's batsmen dominated in fours and sixes, enjoying the highest number of boundary hits. Additionally, they spent the most time at the crease, closely followed by South Africa.

**Indian and South African Brilliance:**
Throughout the tournament, both India and South Africa consistently displayed batting masterclasses, establishing themselves as the top batting orders in the competition.

## Player Statistics Exploration
### Bowling
<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/593698ad-8bdb-4bce-bc9b-0e1865198fb3" alt="Image 1" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/b3f10b67-e2af-4ef6-83c5-7f91ccb2b068" alt="Image 2" width="300" height="300"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/01da84b3-cd76-4a0e-a150-522ded2be09f" alt="Image 3" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/c6db8557-4648-46c2-9266-ba6f7cd549c6" alt="Image 4" width="300" height="300"></td>
    </tr>
  </table>
</div>

Mohammed Shami led the bowling attack with 23 wickets, followed closely by Adam Zampa (22) and Dilshan Madushanka (21). Mitchell Santner and Trent Boult, both from New Zealand, bowled the most, bowling 92 and 91 overs respectively. Jasprit Bumrah and Kuldeep Yadav emerged as the most economical bowlers, boasting figures of 3.7 and 3.9.

**Shami's exceptional performance, with 23 wickets at an economical 4.8, cemented his position as the undisputed bowler of the tournament.*

### Batting
<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/257ef95f-bf3d-40b7-9974-fc6af0d91f79" alt="Image 1" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/67b74bbd-e690-406d-9c36-b591ea208ce4" alt="Image 2" width="300" height="300"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/2d0d3c03-8aa0-4087-b479-ff8a36eef93d" alt="Image 3" width="300" height="300"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/95da8621-f401-4d7b-a344-aa5e7f36973e" alt="Image 4" width="300" height="300"></td>
    </tr>
  </table>
</div>

**Runs Scored:**
Virat Kohli from India claimed the position of the leading run-scorer, with an impressive total of 711 runs. Following closely were Quinton de Kock with 594 runs and Rachin Ravindra with 578 runs.

**Strike Rate and Boundaries:**
David Willey representing England secured the highest strike rate, closely trailed by Aiden Markram. In terms of boundary scoring, Virat Kohli (India) and Rohit Sharma (India) excelled by recording the maximum number of 4s and 6s, respectively.

*Virat Kohli emerged as the standout player of the tournament, not only leading with a remarkable 711 runs but also securing the top position for the maximum number of 4s, earning him the title of Player of the Tournament.*

## Match Outcome Trends

<div align="center">
  <img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/8d4c1cd9-839b-45d7-a803-db352e1e7b49" alt="Image 1" width="500" height="500">
  <img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/44f73b42-d5e6-4d73-8f7b-bdd4446d7e9b" alt="Image 2" width="500" height="500">
</div>

## Temporal Analysis

<div align="center">
  <table>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/d1131938-da10-4a69-b746-efe2b697b978" alt="Pak 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/058145da-cbe2-464d-9d3f-0323a2905c4c" alt="Pak 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/1a001d12-dd88-4165-9824-339a92e84ca5" alt="Eng 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/69fa3763-2b60-491d-98a4-0db9ef85770f" alt="Eng 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/3c33af0d-8293-4345-ba6f-78e5f9ef54c2" alt="NZ 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/7de27490-0f97-4d2c-be91-5e8ce0c9fd28" alt="NZ 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/e3efd8e9-3b5a-47e8-867a-7832423ec7e5" alt="AFG 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/e741ff98-8796-41e5-b806-37c54d2770ff" alt="AFG 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/4e135c9b-967d-4098-a879-65fb838b217f" alt="NED 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/92a64970-5ef3-4e74-bf36-e3157f1817b7" alt="NED 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/d13f4abe-ee00-46af-a8e7-334c55171027" alt="BAN 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/8b80a552-4da6-4061-9e35-d0187649057e" alt="BAN 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/f362e7c0-55a9-4675-ae9f-54260c1faa12" alt="SA 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/d136cde1-960a-46a0-8317-3eddce1ce039" alt="SA 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/67083c94-666e-49a9-8185-9271f52fb326" alt="SL 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/497a016b-9ab2-4d45-a0c1-803d708369f4" alt="SL 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/729405e0-bb04-4584-a04a-a58bb73d40bd" alt="AUS 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/14f4d350-b31e-461e-8a41-7c2e2567a93e" alt="AUS 2" width="500" height="380"></td>
    </tr>
    <tr>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/0be920d9-12fc-4138-aa4a-0b15647976b0" alt="IND 1" width="500" height="380"></td>
      <td><img src="https://github.com/lexxus16/worldcup_2023/assets/69308391/1a5b7c4d-aa18-4a6d-aa92-b6741c2d3d1b" alt="IND 2" width="500" height="380"></td>
    </tr>
  </table>
</div>




## Summary

*In summary, it can be inferred that the most consistently performing teams throughout the tournament were India, Australia, South Africa, and New Zealand. These teams demonstrated commendable performances in both batting and bowling. The 2023 Cricket World Cup was ultimately won by Australia, while India secured the runner-up position.*







