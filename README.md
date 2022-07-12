# js-getweek

    let getWeekday = (s) => {
      const [dd, mm, yyyy] = s.split('-'),
      date = new Date(yyyy, mm - 1, dd);
      return date.toLocaleDateString('es-AR', { weekday: 'long' });
    };
