module.exports = {
  tutorialSidebar: [
    {
      type: 'doc',
      id: 'intro',
      label: 'ホーム',
    },
    {
      type: 'category',
      label: '経理会計',
      items: [
        'keiri/seikyusho-hakko',
        'keiri/seikyusho-juryo',
        {
          type: 'category',
          label: '経費立替',
          items: [
            'keiri/keihi-tatekae/credit-card',
            'keiri/keihi-tatekae/genkin',
            'keiri/keihi-tatekae/koguchi',
          ],
        },
      ],
    },
    {
      type: 'doc',
      id: 'jinji',
      label: '人事労務',
    },
    {
      type: 'doc',
      id: 'somu',
      label: '総務',
    },
    {
      type: 'doc',
      id: 'homu',
      label: '法務',
    },
  ],
};
