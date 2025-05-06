import React from 'react';
import { screen, render } from '@testing-library/react';
import Main from './index';

describe('<main/>', () => {
  it('shold render the heading', () => {
    render(<Main />);
    expect(
      screen.getByRole('heading', {
        name: /Main Component/i,
      }),
    ).toBeInTheDocument();
  });
});
