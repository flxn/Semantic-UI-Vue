<template lang="html">
  <sui-statistics-group :columns="4">
    <sui-statistic inGroup>
      <sui-statistic-value>
        22
      </sui-statistic-value>
      <sui-statistic-label>
        Saves
      </sui-statistic-label>
    </sui-statistic>
    <sui-statistic inGroup>
      <sui-statistic-value text>
        Three<br>
        Thousand
      </sui-statistic-value>
      <sui-statistic-label>
        Signups
      </sui-statistic-label>
    </sui-statistic>
    <sui-statistic inGroup>
      <sui-statistic-value>
        <i class="plane icon"></i> 5
      </sui-statistic-value>
      <sui-statistic-label>
        Flights
      </sui-statistic-label>
    </sui-statistic>
    <sui-statistic inGroup>
      <sui-statistic-value>
        <img src="static/images/avatar/small/joe.jpg" class="ui circular inline image">
        42
      </sui-statistic-value>
      <sui-statistic-label>
        Team Members
      </sui-statistic-label>
    </sui-statistic>
  </sui-statistics-group>
</template>

<script>
export default {
  name: 'StatisticEvenlyDividedExample',
};
</script>